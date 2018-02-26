<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Welfare/>
        <Service/>
        <Footor/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../common/header.vue"
import Footor from "../common/footer.vue"
import Navbar from "../common/navbar.vue"
import Slider from "./islider.vue"
import Welfare from "./welfare.vue"
import Service from "./service.vue"
export default {
    components: {
        Heador,
        Slider,
        Welfare,
        Service,
        Footor,
        Navbar,
    },
}
</script>
