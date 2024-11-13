<h1 class="text-xl font-medium mb-4">Input</h1>
  <label class="form-control sm:w-96">
    <div class="label">
      <span class="label-text">Full Name</span>
    </div>
    <input type="text" placeholder="e.g. John Doe" class="input" />
    <div class="label">
      <span class="label-text-alt">Please write your full name</span>
    </div>
  </label>
  <h1 class="text-xl font-medium my-4">Radio</h1>
  <label class="form-control flex items-center gap-1">
    <input type="radio" name="radio-0" class="radio radio-primary" />
    <span class="label cursor-pointer">
      <span class="label-text text-base">Default</span>
    </span>
  </label>
  <label class="form-control flex items-center gap-1">
    <input
      type="radio"
      name="radio-0"
      class="radio radio-primary"
      Checked
    />
    <span class="label cursor-pointer">
      <span class="label-text text-base">Checked</span>
    </span>
  </label>
  <h1 class="text-xl font-medium my-4">Checkbox</h1>
  <div class="flex items-center gap-2">
    <input
      type="checkbox"
      class="checkbox checkbox-primary mb-1.5"
      id="check1"
    />
    <label class="label-text text-base" for="check1"> Default </label>
  </div>
  <div class="flex items-center gap-2">
    <input
      type="checkbox"
      class="checkbox checkbox-primary"
      id="check3"
      Checked
    />
    <label class="label-text text-base" for="check3"> Checked </label>
  </div>
  <h1 class="text-xl font-medium my-4">Switch</h1>
  <label class="form-control flex items-center gap-1">
    <input type="checkbox" class="switch switch-primary" />
    <span class="label cursor-pointer flex-col items-start">
      <span class="label-text text-base">Default</span>
    </span>
  </label>
  <label class="form-control flex items-center gap-1">
    <input type="checkbox" class="switch switch-primary" Checked />
    <span class="label cursor-pointer flex-col items-start">
      <span class="label-text text-base">Checked</span>
    </span>
  </label>