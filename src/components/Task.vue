<template>
    <div class="task">
        <h3>{{ task.text }}
            <i class="fas fa-times"></i>
        </h3>
        <p>{{ task.day }}</p>    
    </div>
</template>

<script>
export default {
    name: 'Task',
    props: {
        task: Object,
    },
}
</script>