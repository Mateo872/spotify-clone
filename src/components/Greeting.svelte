<script lang="ts">
    const currentTime = new Date()
    const currentHour = currentTime.getHours()

    let greeting = ""

    if(currentHour < 12){
        greeting = "Buenos días"
    }else if(currentHour < 18){
        greeting = "Buenas tardes"
    }else{
        greeting = "Buenas noches"
    }
</script>

<h1 class="text-3xl font-bold my-0">{greeting}</h1>