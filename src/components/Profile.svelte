<script>
  let imgUrl =
    'https://instagram.fscl1-1.fna.fbcdn.net/v/t51.2885-15/e35/s1080x1080/141103402_2127141797439623_5495776787243798893_n.jpg?tp=1&_nc_ht=instagram.fscl1-1.fna.fbcdn.net&_nc_cat=111&_nc_ohc=G_hEwI4kdFcAX_l59pq&ccb=7-4&oh=7eca6421a811b7d19659f43a99b4affb&oe=607C17C6';

  export let nickname;
  export let name;
</script>

<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img src={imgUrl} alt="" />
    </div>
    <div class="Profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>
