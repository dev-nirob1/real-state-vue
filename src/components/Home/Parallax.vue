<template>
<section class="parallax">
            <div class="pop-up-btn">
                <button class="btn-circle btn-center-align">
                    <span class="material-symbols-outlined">
                        play_arrow
                    </span>
                </button>
            </div>
        </section>
</template>

<style scoped>
.parallax {
  background-image:
      linear-gradient(to bottom, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.2)),
      url('../../assets/about-5.jpg');
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
  height: 55vh;
  position: relative;
  margin-bottom: 5rem;
}

.pop-up-btn {
  display: flex;
  align-items: center;
  justify-content: center;
}

</style>