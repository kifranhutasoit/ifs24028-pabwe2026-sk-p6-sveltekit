<script lang="ts">
  import AuthLayout from "$lib/features/auth/layouts/AuthLayout.svelte"; // sesuaikan path
  // ... form logic
</script>

<AuthLayout title="Masuk" subtitle="Lanjutkan belajar dari kursus terakhir Anda.">
  <!-- HANYA form di sini -->
  <form>
    ...
  </form>

  {#snippet footer()}
    Belum punya akun? <a href="/auth/register">Daftar</a>
  {/snippet}
</AuthLayout>