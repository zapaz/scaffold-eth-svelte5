<script lang="ts"></script>

{#snippet pageTest(pageName: string)}
  <li><a class="text-blue-500 hover:underline" href="/tests/{pageName}">{pageName}</a></li>
{/snippet}

<div class="p-8">
  <h1 class="text-2xl font-bold mb-4">Tests</h1>

  <ul class="list-disc pl-5 space-y-2">
    {@render pageTest("connect")}
  </ul>
</div>
