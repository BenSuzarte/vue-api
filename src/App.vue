<template>
  <div>
    <!-- NAVBAR -->
    <nav class="navbar navbar-expand-sm bg-dark navbar-dark">
      <div class="container">
        <a class="navbar-brand order-md-last">API Vue.js + MongoDB + Node.js</a>
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Create New Employee</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/list-employees">List All Employees</router-link>
          </li>
        </ul>
      </div>
    </nav>
    <div class="container mt-5">
      <router-view/>
    </div>
  </div>
</template>
