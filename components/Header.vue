<script lang="ts" setup>
// Columns
const columns = [{
    key: 'id',
    label: 'Номер',
    sortable: true
}, {
    key: 'title',
    label: 'Название',
    sortable: true
}, {
    key: 'completed',
    label: 'Статус',
    sortable: true
}, {
    key: 'actions',
    label: 'Дополнительно',
    sortable: false
}]

// const users = fetch('http://127.0.0.1:8000/')

// console.log(users)
</script>

<template>
    <UCard class="w-full">
        <UBadge>Press -></UBadge>
        <UTextarea></UTextarea>
        <UButton>Press me</UButton>
    </UCard>
</template>