#useForm

Ejemplo de uso:

```

const initialForm = {
    name:"",
    age:0,
    email:""
}

const [formValues, handleInputChange, reset] = useForm(initialForm)

```

en el objeto recibe todos los valores del formulario