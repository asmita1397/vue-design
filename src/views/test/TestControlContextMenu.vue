<template>
  <div>
        <ul class="nav navbar-nav">
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
        <li class="dropdown">
            <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="true"> <span class="nav-label">Services</span> <span class="caret"></span></a>
            <ul class="dropdown-menu">
                <li><a href="#">Service A</a></li>
                <li><a href="#">Service B</a></li>
                <li class="dropdown-submenu">
                    <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false"> <span class="nav-label">Service C</span><span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="#">Service C1</a></li>
                        <li><a href="#">Service C2</a></li>
                        <li><a href="#">Service C3</a></li>
                        <li><a href="#">Service C4</a></li>
                        <li><a href="#">Service C5</a></li>
                    </ul>
                </li>
            </ul>
        </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

</style>