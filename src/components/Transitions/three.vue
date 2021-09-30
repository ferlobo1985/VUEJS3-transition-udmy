<template>
    <div class="form-group">
        <input v-model="name" class="form-control">
    </div>
    <button 
        class="btn btn-primary" 
        @click="addOne"
    >
        Add one
    </button>    
    <hr/>
    <div>
        <ul class="pl-0">

                <li
                    class="list-group-item"
                    v-for="(item) in list"
                    :key="item"
                >
                    {{ item }}
                </li>
  
        </ul>
    </div>

</template>


<script>
    export default {
        data(){
            return{
                list:['Francis','Ron','Martha'],
                name:''
            }
        },
        methods:{
            addOne(){
          
            },
        }
    }
</script>