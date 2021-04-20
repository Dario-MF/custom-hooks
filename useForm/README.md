# UseForm Hook

Ejemplo:
```
    import useForm from 'path';

    const initialForm = {
        name: '',
        age: '',
        email: ''
    };
    const [ formValues, handleValueChange, reset ] = useForm( initialForm );
```

- useForm( initialForm ) // Recive un objeto con estado inicial (defecto {}).
- formValues      // Estado actual del formulario.
- handleValueChange(event)  // Recive evento del input, modifica estado del formulario.
- reset()  // Restaura estado del formulario al inicial.