<template>
    <div class="home">
        <div style="position: absolute; top: 0; z-index: -50;background: center no-repeat url('/cover.jpg'); background-size: cover; height: 100vh; width: 100vw;">
            <div style="background: #000; width: 100%; height: 100%; opacity: .55;"></div>
        </div>
        <div class="container white z-depth-4" style="position: relative; top: 60vh; padding: 2rem 4rem;">
            <h1>A Timeless Question for Japan</h1>
            <p>From the early portions of the Tokugawa era, to modern Japanese society, there has been people who've been
            isolated from receiving the full benefits of their society for many reasons.</p>
            <div class="divider"></div>
            <h2>Historical Turning Points</h2>
            <div class="row">
                <div class="col l6 s12">
                    <div class="card horizontal">
                        <div class="card-image">
                            <div style="background: center no-repeat url('/tokugawa_cover.jpg'); background-size: cover; height: 190px; width:120px"></div>
                        </div>
                        <div class="card-stacked">
                            <div class="card-content">
                                <h4>The Tokugawa Era</h4>
                            </div>
                            <div class="card-action">
                                <router-link to="/tokugawa"><a>Go To Article</a></router-link>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col l6 s12">
                    <div class="card horizontal">
                        <div class="card-image">
                            <img src="https://lorempixel.com/100/190/nature/6">
                        </div>
                        <div class="card-stacked">
                            <div class="card-content">
                                <p>I am a very simple card. I am good at containing small bits of information.</p>
                            </div>
                            <div class="card-action">
                                <a href="#">This is a link</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col l6 s12">
                    <div class="card horizontal">
                        <div class="card-image">
                            <img src="https://lorempixel.com/100/190/nature/6">
                        </div>
                        <div class="card-stacked">
                            <div class="card-content">
                                <p>I am a very simple card. I am good at containing small bits of information.</p>
                            </div>
                            <div class="card-action">
                                <a href="#">This is a link</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col l6 s12">
                    <div class="card horizontal">
                        <div class="card-image">
                            <img src="https://lorempixel.com/100/190/nature/6">
                        </div>
                        <div class="card-stacked">
                            <div class="card-content">
                                <p>I am a very simple card. I am good at containing small bits of information.</p>
                            </div>
                            <div class="card-action">
                                <a href="#">This is a link</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    // @ is an alias to /src
    import HelloWorld from '@/components/HelloWorld.vue'

    export default {
        name: 'home',
        components: {
            HelloWorld
        }
    }
</script>

<style scoped>
    p {
        font-size: 1.4rem;
    }
</style>