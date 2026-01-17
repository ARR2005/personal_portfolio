<template>
    <section>
        <div>

        </div>
        <div>
            <a href=""></a>
        </div>
    </section>
    <section>
        <div>
            <div id="frontend" class="contents"></div>
            <div id="frontend" class="contents"></div>
            <div id="frontend" class="contents"></div>
            <div id="frontend" class="contents"></div>
        </div> 
        <div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            <div id="backend" class="contents"></div>
            
        </div>
    </section>
    <footer>
        <div> </div>
        <div> </div>
        <div> </div>
        <div> </div>
    </footer> 
</template>

<script lang="ts">
import { defineComponent } from 'vue'

    const frontend = {
        Framework:{
            Vite:{
                vue: "Vue",
                react: "React"
            }
        },
        Style:{
            scss:"scss",
            css:"css",
            tailwind:"Tailwind"
        }
    }

    const backend = {
        Language : {
            Static: "Javascript",
            Static2:"Typescript"
        },
        
        Database : {
            Local : "Mysql",
            Router: "Express",
            Router1: "Laravel"
        },

        dist: {
            node:"Node"
        }
    }

export default defineComponent({
    setup () {
        

        return {}
    }
})
</script>

<style scoped>

</style>