<template>
  <div id="main">
    <br />
    <h1>{{title}}</h1>
    <br />
    <p>
      Hi! My name is
      <strong>Lawrence Li</strong> (aka
      <strong>Lonor</strong> elsewhere). I am a backend developer and
      interested in DevOps.
    </p>
    <div>
      <blockquote>
        <p>The amateurs. The outsiders. The autodidacts.</p>
      </blockquote>
    </div>
    <h2>Contact</h2>
    <p>I am currently living in Shanghai, China.</p>
    <p>You can reach me by</p>
    <ul>
      <li>
        <a href="https://t.me/lawrence1975" target="_blank">Telegram</a>
      </li>
      <li>
        <a href="mailto:lonor@live.com" target="_blank">Email</a>
      </li>
    </ul>
    <h2>Projects</h2>
    <p>
      All my open source code can be found on
      <a
        href="https://github.com/Lonor"
        target="_blank"
      >GitHub</a> and they
      are shit code.
    </p>
    <h2>Interaction</h2>
    <p>
      Here's my chinese social site:
      <a
        href="https://www.douban.com/people/jayleehoho/"
        target="_blank"
      >douban</a>,
      <a href="https://www.zhihu.com/people/jayleee/answers" target="_blank">zhihu</a>.
      Actually, I am a fanfou.com
      user, but I'm not
      gonna tell you my account. As
      <a
        href="https://en.wikipedia.org/wiki/Aaron_Swartz"
        target="_blank"
      >
        an
        fundamentalist for open
        web
      </a>, I have my
      <a href="https://blog.lawrenceli.me" target="_blank">blog</a>, despite hardly blogging :)
    </p>
    <h2>Photography</h2>
    <p>
      I don't take photos in daily life. But you can find some on
      <a
        href="https://www.instagram.com/lawrenceli.me/"
        target="_blank"
      >Instagram</a>.
    </p>
  </div>
</template>


<script>
export default {
  name: "About",
    props: {
    title: String
  }
};
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
:root {
  --main-bg-color: #eee;
  --main-text-color: #111;
}
@media (prefers-color-scheme: dark) {
  :root {
    --main-bg-color: #222;
    --main-text-color: #bbb;
  }
}
body {
  font-family: -apple-system, BlinkMacSystemFont, "PingFang SC",
    "Helvetica Neue", STHeiti, "Microsoft Yahei", Tahoma, Simsun, sans-serif;
  background-color: var(--main-bg-color);
  color: var(--main-text-color);
}

p {
  line-height: 1.6rem;
}

#main {
  margin: auto;
  max-width: 39em;
  padding-left: 0.8rem;
  padding-right: 0.8rem;
}

a:link,
a:visited {
  color: var(--main-text-color);
  text-decoration-color: #5e5e5e;
}

blockquote {
  color: #5e5e5e;
  margin: auto;
  padding: 0 1em;
  border-left: 5px solid #5e5e5e;
}
</style>