# MYPDesign
Website For mMel
<div class="card">
  <h2>Progress</h2>

  <!-- YOU (editable) -->
  <div class="friend">
    <strong>You</strong>
    <input type="range" min="0" max="100" value="65"
           oninput="updateProgress(this.value)">
    <div class="progress-bar">
      <div id="youProgress" class="progress" style="width:65%"></div>
    </div>
  </div>

  <!-- FRIENDS (view only) -->
  <div class="friend">Mel
    <div class="progress-bar">
      <div class="progress" style="width:70%"></div>
    </div>
  </div>

  <div class="friend">Alex
    <div class="progress-bar">
      <div class="progress" style="width:50%"></div>
    </div>
  </div>

  <div class="friend">Sam
    <div class="progress-bar">
      <div class="progress" style="width:80%"></div>
    </div>
  </div>

  <div class="friend">Don
    <div class="progress-bar">
      <div class="progress" style="width:60%"></div>
    </div>
  </div>
</div>
