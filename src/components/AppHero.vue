<template>
    <div class="container">
        <div class="card">
            <h1 class="title-card">
                Hello World!
            </h1>
            <div class="text">
                Questo è il mio jumbotron!
            </div>
        </div>
    </div>
</template>

<style>
.container{
    background-image: url(../assets/MK4251M.jpg);
    background-size: cover;
    margin: 0 auto;
    padding: 20px;
}

.card{
    background-color: rgba(39, 32, 32, 0.645);
    border-radius: 20px;
    color: white;
    font-size: 20px;
}

.title-card{
    border-top: 1px solid currentColor;
}

.text{
    border-bottom: 1px solid currentColor;
}

.title-card,
.text{
    padding: 10px;
    border-radius: 30px;
}
</style>