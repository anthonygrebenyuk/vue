<template>
    <div>
        <h1>Добавление товара</h1>
        <form action="">
            <input type="text" placeholder="Наименование" v-model="name">
            <input type="text" placeholder="Цена" v-model="price">
            <button type="button" class="btn btn-primary" @click="addItem">Добавить</button>
        </form>
    </div>
</template>

<script>
    export default {
        data: function () {
            return {
                posts: [
                    { id: 1, title: 'My journey with Vue' },
                    { id: 2, title: 'Blogging with Vue' },
                    { id: 3, title: 'Why Vue is so fun' }
                ]
            }
        }
    }
</script>
