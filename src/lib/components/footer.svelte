<script lang="ts">
  import ThemeSwitcher from './theme-switcher.svelte';
  import PackageVersion from './package-version.svelte';
</script>

<footer class="mt-auto w-full bg-skin-off-background py-4">
  <div class="mx-auto flex w-[90%] max-w-[1440px] items-center justify-start gap-10">
    <ThemeSwitcher />
    <PackageVersion />

    <ul class="flex list-none items-center gap-6 ml-auto">
      <!-- Discord -->
      <li>
        <a
          data-test-id="discord-btn"
          href="https://discord.eddiehub.org"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="Discord"
          class="transition duration-200 text-gray-500 hover:text-[#5865F2]"
        >
          <i class="fa-brands fa-discord fa-xl"></i>
        </a>
      </li>

      <!-- GitHub -->
      <li>
        <a
          data-test-id="github-btn"
          href="https://github.eddiehub.org"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="GitHub"
          class="transition duration-200 text-gray-500 hover:text-black dark:hover:text-white"
        >
          <i class="fa-brands fa-github fa-xl"></i>
        </a>
      </li>

      <!-- LinkedIn -->
      <li>
        <a
          data-test-id="linkedin-btn"
          href="https://linkedin.com/company/eddiehub"
          target="_blank"
          rel="noopener noreferrer"
          aria-label="LinkedIn"
          class="transition duration-200 text-gray-500 hover:text-[#0A66C2]"
        >
          <i class="fa-brands fa-linkedin fa-xl"></i>
        </a>
      </li>
    </ul>
  </div>
</footer>
<!-- i fix hover color in footer -->
