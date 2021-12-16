<script>
    import Tooltip from "./Tooltip.svelte"
</script>

<details>
    <summary>
        Hello. My name is Ella, and I am a senior at Foothill High School. This is my art portfolio for Semester 1. <span class="more">Read more...</span>
    </summary><br/>
    <span class="description">
        My work samples a variety of art styles but is concentrated in digital mediums. I love to create interactive web experiences that are memorable, fun, and usable. I work with digital mediums for the freedom, accessibility, and powerful platform that the web provides. The concept of open source is hackable by design which makes it a perfect medium for exploring the intersection of design and usability. 
    </span>
    <br/><br/>
    <span class="description dotted-underline">
       <Tooltip title="This website is open source on GitHub!"><a href="https://github.com/eilla1/receipt-website" target="_blank" class="dotted-underline" style="color: black">Open source?</a></Tooltip>
    </span>
</details>

<style>
    details {
        margin-bottom: 20px;
    }

    .more {
        color: blue;
        text-decoration: underline;
        text-decoration-style: dotted;
        cursor: pointer;
    }

    details {
        line-height: 1em;
    }
</style>