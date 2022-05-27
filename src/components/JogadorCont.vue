<script>
    export default {}
</script>

<template>
    <div class="container">
        <form>
            <div class="input-group mb-3">
                <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">Opções</button>
                <ul class="dropdown-menu row">
                    <li><a class="dropdown-item" href="#">Opção 1</a></li>
                    <li><a class="dropdown-item" href="#">Opção 2</a></li>
                    <li><a class="dropdown-item" href="#">Opção 3</a></li>
                    <li><a class="dropdown-item" href="#">Opção 4</a></li>
                    <li><a class="dropdown-item" href="#">Opção 5</a></li>
                </ul>
                <input type="text" class="form-control" aria-label="Text input with dropdown button">
                <button class="btn btn-outline-secondary" type="button" id="button-addon2">pesquisar</button>
            </div>
        </form>
        <div class="col-12 text-center">
            <label for="item-1"><h3 class="btn btn-outline-secondary">Mostrar Tabela</h3></label>
            <input type="checkbox" name="item" id="item-1">
            <form id="tabela">
                <div class="form-group">
                    <ul class="list-group row">
                        <li class="list-group-item">Gabriel Barbosa – 26,00 mi. €</li>
                        <li class="list-group-item">Danilo – 22,00 mi. €</li>
                        <li class="list-group-item">Giorgian de Arrascaeta – 19,00 mi. €</li>
                        <li class="list-group-item">Guilherme Arana – 14,00 mi. €</li>
                        <li class="list-group-item">Patrick de Paula – 16,00 mi. €</li>
                        <li class="list-group-item">Matías Zaracho – 17,50 mi. €</li>
                        <li class="list-group-item">Dudu – 15,00 mi. €</li>
                        <li class="list-group-item">Raphael Veiga – 12,00 mi. €</li>
                        <li class="list-group-item">Gabriel Veron – 25,00 mi. €</li>
                        <li class="list-group-item">Luiz Henrique – 12,00 mi. €</li>
                    </ul>
                </div>
            </form>
        </div>
    </div>
</template>