<!-- DEV ONLY IMPORTS -->
<div class="selectContainer multiSelect">
    <div class="multiSelectItem">
      <div class="multiSelectItem_label">
        Pizza
      </div>
      <div class="multiSelectItem_clear">
        <svg width="100%" height="100%" viewBox="-2 -2 50 50" focusable="false" role="presentation">
          <path
            d="M34.923,37.251L24,26.328L13.077,37.251L9.436,33.61l10.923-10.923L9.436,11.765l3.641-3.641L24,19.047L34.923,8.124 l3.641,3.641L27.641,22.688L38.564,33.61L34.923,37.251z"></path>
        </svg>
      </div>
    </div>
    <div class="multiSelectItem">
      <div class="multiSelectItem_label">
        Chips
      </div>
      <div class="multiSelectItem_clear">
        <svg width="100%" height="100%" viewBox="-2 -2 50 50" focusable="false" role="presentation">
          <path
            d="M34.923,37.251L24,26.328L13.077,37.251L9.436,33.61l10.923-10.923L9.436,11.765l3.641-3.641L24,19.047L34.923,8.124 l3.641,3.641L27.641,22.688L38.564,33.61L34.923,37.251z"></path>
        </svg>
      </div>
    </div>
  <input autocomplete="off" autocorrect="off" spellcheck="true" placeholder="">
  <div class="clearSelect">
    <svg width="100%" height="100%" viewBox="-2 -2 50 50" focusable="false" role="presentation">
      <path fill="currentColor"
            d="M34.923,37.251L24,26.328L13.077,37.251L9.436,33.61l10.923-10.923L9.436,11.765l3.641-3.641L24,19.047L34.923,8.124 l3.641,3.641L27.641,22.688L38.564,33.61L34.923,37.251z"></path>
    </svg>
  </div>
</div>

<style>
  .selectContainer {
    border: 1px solid #D8DBDF;
    border-radius: 3px;
    height: 42px;
    position: relative;
  }

  .selectContainer input {
    border: none;
    color: #3F4F5F;
    height: 42px;
    line-height: 42px;
    padding: 0 16px;
    width: 100%;
    background: transparent;
    font-size: 14px;
    letter-spacing: -0.08px;
  }

  .selectContainer input::placeholder {
    color: #78848F;
  }

  .selectContainer:hover {
    border-color: #b2b8bf;
  }

  .selectContainer input:focus {
    outline: none;
  }

  .clearSelect {
    position: absolute;
    right: 10px;
    top: 12px;
    width: 20px;
    height: 20px;
    color: #c5cacf;
  }

  .clearSelect:hover {
    color: #2c3e50;
  }

  .multiSelect {
    display: flex;
    padding: 0 16px;
  }
  
  .multiSelectItem {
    background: #E8EAED;
    margin-right: 5px;
    border-radius: 4px;
    line-height: 26px;
    display: flex;
    cursor: default;
  }

  .multiSelectItem_label {
    padding: 0 5px 0 10px;
  }

  .selectContainer.multiSelect input {
    width: auto;
    padding: 0;
    flex-grow: 1;
  }

  .multiSelectItem_clear {
    border-radius: 0 4px 4px 0;
    width: 20px;
    text-align: center;
  }

  .multiSelectItem_clear:hover {
    background-color: red;
  }

  .multiSelectItem_clear svg {
    width: 14px;
    height: 14px;
    position: relative;
    top: 3px;
  }
</style>
