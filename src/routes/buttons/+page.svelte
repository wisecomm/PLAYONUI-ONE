<script>
  import Button from  "../../components/Button.svelte"; 
</script>

<svelte:head>
  <title>Buttons</title>
  <meta name="description" content="Buttons" />
</svelte:head>


<div>
  <h1 class="text-xl font-medium mb-4">Solid Buttons</h1>
  <div class="flex gap-2 flex-wrap">
    <Button label="Primary" addClass="btn-primary" />
    <Button label="Info" addClass="btn-info" />
    <Button label="Success" addClass="btn-success" />
    <Button label="Warning" addClass="btn-warning" />
    <Button label="Error" addClass="btn-error" />
  </div>

  <h1 class="text-xl font-medium my-4">Soft Buttons</h1>
  <div class="flex gap-2 flex-wrap">
    <Button label="Primary" addClass="btn-primary btn-soft" />
    <Button label="Info" addClass="btn-info btn-soft" />
    <Button label="Success" addClass="btn-success btn-soft" />
    <Button label="Warning" addClass="btn-warning btn-soft" />
    <Button label="Error" addClass="btn-error btn-soft" />
  </div>

  <h1 class="text-xl font-medium my-4">Outline Buttons</h1>
  <div class="flex gap-2 flex-wrap">
    <Button label="Primary" addClass="btn-primary btn-outline" />
    <Button label="Info" addClass="btn-info btn-outline" />
    <Button label="Success" addClass="btn-success btn-outline" />
    <Button label="Warning" addClass="btn-warning btn-outline" />
    <Button label="Error" addClass="btn-error btn-outline" />
  </div>

  <h1 class="text-xl font-medium my-4">Text Buttons</h1>
  <div class="flex gap-2 flex-wrap">
    <Button label="Primary" addClass="btn-primary btn-text" />
    <Button label="Info" addClass="btn-info btn-text" />
    <Button label="Success" addClass="btn-success btn-text" />
    <Button label="Warning" addClass="btn-warning btn-text" />
    <Button label="Error" addClass="btn-error btn-text" />
  </div>

  <h1 class="text-xl font-medium my-4">Gradient Buttons</h1>
  <div class="flex gap-2 flex-wrap">
    <Button label="Primary" addClass="btn-primary btn-gradient" />
    <Button label="Info" addClass="btn-info btn-gradient" />
    <Button label="Success" addClass="btn-success btn-gradient" />
    <Button label="Warning" addClass="btn-warning btn-gradient" />
    <Button label="Error" addClass="btn-error btn-gradient" />
  </div>
</div>


