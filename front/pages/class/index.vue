<template>
    <div>
        <PageLayout>

        </PageLayout>
    </div>
</template>
<script>
import PageLayout from "@/components/PageLayout"
export default {
	name: 'Class',
    created() {
        this.$axios.get('api/params').than(res => console.log(res))
    },  
	components: {
		PageLayout,
	},
}

</script>
<style lang="">
    
</style>