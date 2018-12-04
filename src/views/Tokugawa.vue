<template>
    <div class="home">
        <div style="position: absolute; top: 0; z-index: -50;background: center no-repeat url('/tokugawa_cover.jpg'); background-size: cover; height: 100vh; width: 100vw;">
            <div style="background: linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55),rgba(51,51,51,1)); width: 100%; height: 100%;"></div>
        </div>
        <div class="container white z-depth-4" style="position: relative; top: 60vh; padding: 2rem 4rem;">
            <h1>Tokugawa Era</h1>
            <h2>Japanese Societal Structure</h2>
            <p>
                The Tokugawa period marks the first time we see a modern societal structure within a newly unified Japan.
                Based on Chinese Confucianism, society under the regime was broken into four classes and arranged
                hierarchically. (Gordon, p.18)
            </p>
            <div class="row">
                <div class="col s12 l3" style="height: 600px; background: url('/nihonnoruutsu-yayoi-rice1.jpg'); background-size: cover;">
                    <h3 class="img-title">Farmers</h3>
                </div>
                <div class="col s12 l3" style="height: 600px; background: url('/01masanobu_yoshiwara.jpg') center; background-size: cover;">
                    <h3 class="img-title">Merchants</h3>
                </div>
                <div class="col s12 l3" style="height: 600px; background: url('/55346-large.jpg') center; background-size: cover;">
                    <h3 class="img-title">Warriors</h3>
                </div>
                <div class="col s12 l3" style="height: 600px; background: url('/edo-3.jpg'); background-size: cover;">
                    <h3 class="img-title">Artisans</h3>
                </div>
            </div>
            <h2>Outside Of The Structure</h2>
            <p>
                However, if one did not fit within the four class structures, they were considered outcasts.
                These outcasts were delegated work that was considered lower from society, like burials, executions, and
                the handling of animal carcasses. (Gordon, p.18)
            </p>
            <img src="/ainu.jpeg" style="width: 100%;">
            <h4>The Politics Of The Time</h4>
            <p>
                The Tokugawa’s criteria for Japanese society also extended to religion and trade. The religious temples
                were regulated along with compulsory registration by all citizens. The goal for these rules was to
                prevent the temples becoming too powerful as they did in the past to challenge the Tokugawa authority.
            </p>
            <p>
                Women in Tokugawa society had varying degree of being considered as part of Japanese society.
                Opportunities for women varied depending on the function of the economic class and social status.
                However, you can only rely on generalizations loosely because everything varied between regions.
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Tokugawa"
    }
</script>

<style scoped>
    p {
        text-indent: 1rem;
    }
    .img-title {
        color: white;
        background: rgba(25,25,25,.75);
        display: inline-flex;
        padding: 0 5px;
    }
</style>