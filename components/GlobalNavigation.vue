<template>
    <header>
        <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
                <a class="navbar-item" href="/">
                    <img src="/assets/images/logo.svg" width="112" height="28">
                </a>

                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>

            <div id="navbarBasicExample" class="navbar-menu">
                <div class="navbar-start">
                    <a class="navbar-item">
                        Home
                    </a>

                    <a class="navbar-item">
                        Documentation
                    </a>

                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">
                            More
                        </a>

                        <div class="navbar-dropdown">
                            <a class="navbar-item">
                                About
                            </a>
                            <a class="navbar-item">
                                Jobs
                            </a>
                            <a class="navbar-item">
                                Contact
                            </a>
                            <hr class="navbar-divider">
                            <a class="navbar-item">
                                Report an issue
                            </a>
                        </div>
                    </div>
                </div>

                <div class="navbar-end">
                    <div class="navbar-item">
                        <div class="buttons">
                            <a class="button is-primary">
                                <strong>Sign up</strong>
                            </a>
                            <a class="button is-light">
                                Log in
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
        <nav>
            <div class="columns">
                <div class="column">
                    <ul class="menu-list">
                        <li><NuxtLink to="/">Home</NuxtLink></li>
                        <li><NuxtLink to="/about">About</NuxtLink></li>
                        <li><NuxtLink to="/blog">Blog</NuxtLink></li>
                        <li><NuxtLink to="/case-studies">Case Studies</NuxtLink></li>
                        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
                        <li><NuxtLink to="/courses">Courses</NuxtLink></li>
                        <li><NuxtLink to="/experience">Experience</NuxtLink></li>
                    </ul>
                </div>
                <div class="column">
                    <ul class="menu-list">
                        <li><NuxtLink to="/presentations">Presentations</NuxtLink></li>
                        <li><NuxtLink to="/services">Services</NuxtLink></li>
                        <li><NuxtLink to="/speaking">Speaking</NuxtLink></li>
                        <li><NuxtLink to="/technologies">Technologies</NuxtLink></li>
                        <li><NuxtLink to="/tutorials">Tutorials</NuxtLink></li>
                        <li><NuxtLink to="/uses">Uses</NuxtLink></li>
                        <li><NuxtLink to="/workshops">Workshops</NuxtLink></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>
</template>

<script setup lang="ts">
</script>