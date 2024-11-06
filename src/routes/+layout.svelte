<script lang="ts">
	import '@picocss/pico';
</script>

<nav class="container-fluid">
    <ul>
      <li><strong>Home</strong></li>
    </ul>
    <ul>
      <li>
        <details class="dropdown">
          <summary>
            Lessons
          </summary>
          <ul dir="rtl">
            <li><a href="#">Lesson 1</a></li>
            <li><a href="#">Lesson 2</a></li>
            <li><a href="#">Lesson 3</a></li>
          </ul>
        </details>
      </li>
      <li><a href="#" class="contrast">Examples</a></li>
      <li><a href="#" class="contrast">Documentation</a></li>
    </ul>
  </nav>

<main>
	<slot />
</main>

<footer>
	<p class="container">&REG; 2024 
        <a href="https://github.com/cjrdz" target="_blank">Github</a>
    </p>
</footer>
