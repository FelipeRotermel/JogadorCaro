<script>
    export default {}
</script>

<template>
    <nav class="navbar navbar-expand-lg navbar-light">
        <a class="navbar-brand" href="#"><h2>JogadorCaro</h2></a>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item active">
                    <RouterLink to="/"><h4 class="text-white">Home</h4></RouterLink>
                </li>
                <li class="nav-item">
                    <RouterLink to="/about"><h4 class="text-white">Custo Time</h4></RouterLink>
                </li>
                <li class="nav-item">
                    <RouterLink to="/jogador"><h4 class="text-white">Custo Jogador</h4></RouterLink>
                    <RouterView />
                </li>
            </ul>
        </div>
    </nav>
</template>