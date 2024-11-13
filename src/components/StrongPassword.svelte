<div>
    <div class="flex mb-2">
      <div class="flex-1">
        <input
          type="password"
          id="password-hints"
          class="input"
          placeholder="Enter password"
        />
        <div
          data-strong-password={`{
        "target": "#password-hints",
        "hints": "#password-hints-content",
        "stripClasses": "strong-password:opacity-100 strong-password-accepted:bg-teal-500 h-2 flex-auto rounded-full bg-primary opacity-40 mx-1"
      }`}
          class="-mx-1 mt-2.5 flex"
        ></div>
      </div>
    </div>
    <div id="password-hints-content" class="mb-3">
      <div>
        <span class="text-sm text-base-content/90">Level:</span>
        <span
          data-pw-strength-hint='["Empty", "Weak", "Medium", "Strong", "Very Strong", "Super Strong"]'
          class="text-base-content/90 text-sm font-semibold"
        >
        </span>
      </div>
      <h6 class="my-2 text-base font-semibold text-base-content/90">
        Your password must contain:
      </h6>
      <ul class="text-base-content/80 space-y-1 text-sm">
        <li
          data-pw-strength-rule="min-length"
          class="strong-password-active:text-success flex items-center gap-x-2"
        >
          <span
            class="icon-[tabler--circle-check] hidden size-5 flex-shrink-0"
            data-check
          ></span>
          <span
            class="icon-[tabler--circle-x] hidden size-5 flex-shrink-0"
            data-uncheck
          ></span>
          Minimum number of characters is 6.
        </li>
        <li
          data-pw-strength-rule="lowercase"
          class="strong-password-active:text-success flex items-center gap-x-2"
        >
          <span
            class="icon-[tabler--circle-check] hidden size-5 flex-shrink-0"
            data-check
          ></span>
          <span
            class="icon-[tabler--circle-x] hidden size-5 flex-shrink-0"
            data-uncheck
          ></span>
          Should contain lowercase.
        </li>
        <li
          data-pw-strength-rule="uppercase"
          class="strong-password-active:text-success flex items-center gap-x-2"
        >
          <span
            class="icon-[tabler--circle-check] hidden size-5 flex-shrink-0"
            data-check
          ></span>
          <span
            class="icon-[tabler--circle-x] hidden size-5 flex-shrink-0"
            data-uncheck
          ></span>
          Should contain uppercase.
        </li>
        <li
          data-pw-strength-rule="numbers"
          class="strong-password-active:text-success flex items-center gap-x-2"
        >
          <span
            class="icon-[tabler--circle-check] hidden size-5 flex-shrink-0"
            data-check
          ></span>
          <span
            class="icon-[tabler--circle-x] hidden size-5 flex-shrink-0"
            data-uncheck
          ></span>
          Should contain numbers.
        </li>
        <li
          data-pw-strength-rule="special-characters"
          class="strong-password-active:text-success flex items-center gap-x-2"
        >
          <span
            class="icon-[tabler--circle-check] hidden size-5 flex-shrink-0"
            data-check
          ></span>
          <span
            class="icon-[tabler--circle-x] hidden size-5 flex-shrink-0"
            data-uncheck
          ></span>
          Should contain special characters.
        </li>
      </ul>
    </div>
  </div>