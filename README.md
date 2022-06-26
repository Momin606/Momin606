### Hi there 👋
<div align="center">
    <img src="image.svg" width="400" height="400" alt="css-in-readme">
</div>

<!-- A big thank you to Prantham for the inspiration: https://twitter.com/Prathkum/status/1392434632935841793 -->

<h1>Hello, my name is Momin.</h1>
<p class="subtitle">Welcome to my Github!</p>
  <foreignObject width="100%" height="100%">
<style>

:root {
  --bg-color: hsl(49 37% 94%);
  --typewriterSpeed: 6s;
  --typewriterCharacters: 24;
}

body {
  margin: 0;
  font-family: "Source Sans Pro", sans-serif;
  min-height: 100vh;
  display: grid;
  place-content: center;
  text-align: center;
  background: var(--bg-color);
}

h1 {
  font-size: clamp(1rem, 3vw + 1rem, 4rem);
  position: relative;
  font-family: "Source Code Pro", monospace;
  position: relative;
  width: max-content;
}

h1::before,
h1::after {
  content: "";
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}

h1::before {
  background: var(--bg-color);
  animation: typewriter var(--typewriterSpeed)
    steps(var(--typewriterCharacters)) 1s forwards;
}

h1::after {
  width: 0.125em;
  background: black;
  animation: typewriter var(--typewriterSpeed)
      steps(var(--typewriterCharacters)) 1s forwards,
    blink 750ms steps(var(--typewriterCharacters)) infinite;
}

.subtitle {
  color: hsl(0 0% 0% / 0.7);
  font-size: 2rem;
  font-weight: 400;
  opacity: 0;
  transform: translateY(3rem);
  animation: fadeInUp 2s ease calc(var(--typewriterSpeed) + 2s) forwards;
}

@keyframes typewriter {
  to {
    left: 100%;
  }
}

@keyframes blink {
  to {
    background: transparent;
  }
}

@keyframes fadeInUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

#yt-link {
  position: absolute;
  bottom: 2em;
  width: 100%;
  color: hsl(0 0 0 / 0.7);

  &:hover,
  &:focus {
    color: teal;
  }
}

<!--
**Momin606/Momin606** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
