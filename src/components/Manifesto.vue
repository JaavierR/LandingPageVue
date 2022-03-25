<script setup>
</script>

<template>
    <p class="value-proposition">Nuestra misión es apoyar a las personas en su busqueda por una alimentación más saludable y sustentable</p>
    <section class="manifesto">
        <div class="card">
            <h3>Seguimiento</h3>
            <p>
                ¿Recuerdas que comiste hace tres semanas? Te ayudamos a llevar un registro de las porciones de alimentos que consumes.
                Información accesible por tu nutricionista para una asistencia más eficiente.
            </p>
        </div>
        <div class="card">
            <h3>Metas</h3>
            <p>Fija metas en conjunto a tu nutricionista. Avanza paso a paso y ve como tu progreso se transforma en resultados.</p>
        </div>
        <div class="card">
            <h3>Alimentos</h3>
            <p>Toda la información que necesitas: grupos de alimentos y listas de alimentos con sus porciones. Lleva la pauta a dónde sea con tu celular.</p>
        </div>
    </section>
    <div class="action">
        <p>Inscribete para recibir la primera versión y ayudanos a crear tu solución ideal</p>
    </div>
</template>

<style>
.value-proposition {
    text-align: center;
    font-size: 2rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: gray;
    margin: 3rem 25%;
}
.manifesto {
    display: flex;
    justify-content: space-evenly;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.card {
    width: 33.3%;
}
.card h3 {
    color: slategrey;
    font-size: 1.5rem;
    text-align: center;
}
.card p {
    padding: 1rem 5rem;
    text-align: justify;
}
.action {
    background-color: mediumaquamarine;
    padding: 3rem 3rem;
    text-align: center;
    font-size: 2rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-weight: bold;
    color:darkslategray;
}
</style>