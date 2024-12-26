<script lang="ts">
  import Sidebar from './lib/Sidebar.svelte';
</script>

<main>
  <div class="main-container">
    <Sidebar />
    <div class="territorio-container">
      <img src="/static/image.png" alt="Mapa de los territorios" />
    </div>
  </div>
</main>

<style >
  .main-container {
    margin: 0;
    padding: 0;
    display: flex;
    align-items: center;
    height: 100vh;
  }

  .territorio-container {
    margin: 0 auto;
    background-color: #f5f5f5;
    border-radius: 5px;
    overflow: hidden;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
  }
</style>
