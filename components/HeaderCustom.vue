<template>
    <div class="header-fixed">
        <div class="container">
            <a-row type="flex" class="header">
              <a-col :span="16">
                <div class="navbar">
                    <a class="navbar-brand" href="https://otomoto.id/">
                        <img src="https://jubelmoto.otomoto.id/images/logo/otomoto-dark.png" width="150" class="logo-dark">
                    </a>
                    <div class="navbar-collapse">
                        <ul class="navbar-nav">
                            <li class="nav-item" tabindex="0">
                                <NuxtLink to="/solusi">Solusi</NuxtLink>
                            </li>
                            <li class="nav-item current" tabindex="0">
                                <NuxtLink to="/solusi">Jubelmoto</NuxtLink>
                            </li>
                            <li class="nav-item" tabindex="0">
                                <NuxtLink to="/solusi">Mitra</NuxtLink>
                            </li>
                            <li class="nav-item" tabindex="0">
                                <NuxtLink to="/solusi">Pertanyaan</NuxtLink>
                            </li>
                            <li class="nav-item" tabindex="0">
                                <NuxtLink to="/solusi">Tips</NuxtLink>
                            </li>
                            
                        </ul>
                    </div>
                </div>
              </a-col>
              <a-col :span="8">
                <div class="navbar-contact">
                    <div>
                        <span> Kontak JubelMoto </span>
                        <strong style="font-weight: 700"> 0813 8777 7876 </strong>
                    </div>
                </div>
              </a-col>
            </a-row>
        </div>
    </div>
</template>

<script>
export default {
    name: "header-custom"
}
</script>
