<template>
  <div id="root">
    <nav>
      <div class="playername">CROWFALL CHARACTER PLANNER</div>
      <ul>
        <!-- <li><a href="/">Home</a></li>
        <li><a href="/">Tools</a></li> -->
        <li><a href="https://discord.gg/ukKmXVP" target="_blank">Discord</a></li>
        <li><a href="https://crusaderw.com" target="_blank">Guides</a></li>
        <li><a href="https://crusaderw.com/about-me/" target="_blank">About</a></li>
        <li><a href="https://crusaderw.com/datenschutzerklaerung/" target="_blank">Privacy</a></li>
        <li><a href="https://gitreports.com/issue/ArcAnya/CrowfallLogs" target="_blank"><button>Report a bug</button></a></li>
        <!-- <li><button>Sign Up</button></li> -->
      </ul>
    </nav>
  </div>
</template>


<script>
export default {
  name: "NavigationBar",
  data() {
    return {
      title: "Navigation Bar",
    };
  },
};
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: none;
}
nav ul {
  display: flex;
  background-color: grey;
  list-style-type: none;
  padding: 0.5em;
  margin: 0.5em;
}
nav li {
  display: flex;
  align-items: center;
  background-color: white;
}
nav a {
  display: inline-block;
  padding: 0.5em;
  margin: 0.2em;
  color: var(--clr-primary);
  text-decoration: none;
}
nav a:hover {
  color: grey;
}
nav img {
  width: 3em;
  height: 3em;
}
.playername {
  display: block;
  justify-content: flex-start;
  background-color: none;
  padding: 0.5em;
  margin: 0.5em;
}
/* nav button {
  padding: 0.5em;
  margin: 0.5em;
  border-radius: 10%;
} */
</style> 