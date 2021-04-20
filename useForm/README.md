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

- useForm( initialForm ) // Recibe un objeto con estado inicial (defecto {}).
- formValues      // Estado actual del formulario.
- handleValueChange(event)  // Recibe evento del input, modifica estado del formulario.
- reset()  // Restaura estado del formulario al inicial.