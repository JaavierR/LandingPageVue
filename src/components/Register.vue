<script setup>
</script>

<template>
    <form name="contact" method="post" data-netlify="true" data-netlify-honeypot="bot-field">
        <input type="hidden" name="contact" value="contact" />
        <div class="form" id="registro">
            <div class="form-title">
                <p>Formulario de registro</p>
            </div>
            <div class="text-input">
                <input type="text" name="firstname" placeholder="Nombre" required>
                <input type="text" name="lastname" placeholder="Apellido" required>
                <input type="email" name="email" placeholder="Correo" required>
            </div>
            <div class="form-radio">
                <input type="radio" name="user" id="paciente" required>
                <label for="paciente">Soy paciente</label>
            </div>
            <div class="form-radio">
                <input type="radio" name="user" id="nutri">
                <label for="nutri">Soy nutri</label>
            </div>
            <button type="submit"> Registrarme </button>
        </div>
    </form>
</template>

<style>
.form  {
    width: 33.3%;
    margin: 2rem auto;
    align-items: center;
}
.form-title {
    text-align: center;
    font-size: 1.5rem;
    font-weight: bold;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: darkslategray;
}
.text-input input{
    width: 100%;
    margin: 1rem 0rem;
    height: 2rem;
    border: 2px solid mediumaquamarine;
    border-radius: 3px;
}
.form-radio {
    width: auto;
    margin: 1rem 2rem;
    font-size: 1rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.form-radio label{
    padding: 0.5rem;
}
.form button {
    width: 100%;
    font-size: 1.5rem;
    font-weight: bold;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: mediumaquamarine;
    padding: 0.5rem 0rem;
    border-radius: 3px;
}
.form button:hover {
    background-color: aquamarine;
}
</style>
