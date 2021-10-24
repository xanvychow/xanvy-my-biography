<script>
    import Header from '$lib/Header.svelte';
    import Section from '$lib/Section.svelte';
    import Hobbies from '$lib/Hobbies.svelte';
    import Personality from '$lib/Personality.svelte';
    let myInfo = {
        title: "Info",
        item1: "Xanvy Chow",
        item2: "15",
        item3: "Chung Ling Private High School"
    };
    let myHobbies = {
        title: "Hobbies",
        item1: "Reading",
        item2: "PLaying computer games",
        item3: "Swimming"
    };
    let myPersonality = {
        title: "Personality",
        item1: "Quiet",
        item2: "HUmble",
        item3: "Kind"
    }
</script>

<Header title="My Biography" />
<Section {...myInfo} />
<Hobbies {...myHobbies} />
<Personality {...myPersonality} />