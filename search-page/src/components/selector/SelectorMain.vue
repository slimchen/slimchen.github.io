<template>
    <div>
        <Selector :select="select"></Selector>
        <Selector :select="selectChild1"></Selector>
    </div>
</template>

<script>
import Selector from "./Selector.vue"
export default {
    name: "SelectorMain",
    components: { Selector },
    data() {
        return {
            select: {
                result:"", 
                name: "Make",
                change:(data) => {
                    console.log(data)
                    this.selectChild1.result=''
                    this.selectChild1.data=data
                },
                data: [{
                    value: 'Volkswagen',
                    label: 'Volkswagen',
                    children:[
                        {
                            value: "Bora",
                            label: "Bora"
                        },
                        {
                            value: "Caddy",
                            label: "Caddy"
                        }
                    ]
                }, {
                    value: 'Volvo',
                    label: 'Volvo',
                    children:[
                        {
                            value: "S60",
                            label: "S60"
                        },
                        {
                            value: "XC60",
                            label: "XC60"
                        }
                    ]
                }],
            },
            selectChild1: {
                result:"", 
                name: "Family",
                data:[]
            },
        }
    }
}
</script>

<style scoped></style>