<template lang="">
    <div>
        <h2>About</h2>

        <p>{{count}}</p>
        <button @click="incre">증가</button>

    </div>
</template>

<script setup>
    const aa = useState('g',()=>'about내용쪽에 있는 데이터....');
</script>

<script>
export default {
    data(){
        return{
            count:100
        }
    },
    methods:{
        incre(){
            this.count++;           
        }
    }
}
</script>