<template>
    {{projectData.ProjectsArray}}

    <div class="project-card"
    v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
        <h2>{{projectData.ProjectsArray[index].Title}}</h2>
        <img src="projectData.ProjectsArray[index].Image" alt="Project image not found">
    </div>
</template>

<script>
import jsonData from "/projects.json"
export default {
    data(){
        return{
            projectData: jsonData
        }
    }
}


</script>

<style>
    .project-card img{
        height: 5rem;
    }
</style>