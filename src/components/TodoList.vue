<template>
    <div>
        <div>
            <input type="text">
            <button>추가하기</button>
        </div>
        <ul>
            <ListItem></ListItem>
        </ul>
    </div>
</template>
<script>
import ListItem from './ListItem'
export default {
    components: { ListItem }
}
</script>
<style>
    
</style>