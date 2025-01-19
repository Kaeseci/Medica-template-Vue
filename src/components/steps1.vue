<template>
  <div class="steps1-container1 thq-section-padding">
    <div class="steps1-max-width thq-section-max-width">
      <div class="steps1-container2">
        <div class="steps1-container3 thq-card">
          <img
            :alt="step1ImageAlt"
            :src="step1ImageSrc"
            class="steps1-image1 thq-img-ratio-1-1"
          />
          <h2 class="thq-heading-2">{{ step1Title }}</h2>
          <span class="steps1-text11 thq-body-small">{{ step1Description }}</span>
          <label class="steps1-text12 thq-heading-3">01</label>
        </div>
        <div class="steps1-container4 thq-card">
          <img
            :alt="step2Alt"
            :src="step2ImageSrc"
            class="steps1-image2 thq-img-ratio-1-1"
          />
          <h2 class="thq-heading-2">{{ step2Title }}</h2>
          <span class="steps1-text14 thq-body-small">{{ step2Description }}</span>
          <label class="steps1-text15 thq-heading-3">02</label>
        </div>
      </div>
      <div class="steps1-container5">
        <div class="steps1-container6 thq-card">
          <img
            :alt="step3ImageAlt"
            :src="step3ImageSrc"
            class="steps1-image3 thq-img-ratio-1-1"
          />
          <h2 class="thq-heading-2">{{ step3Title }}</h2>
          <span class="steps1-text17 thq-body-small">{{ step3Description }}</span>
          <label class="steps1-text18 thq-heading-3">03</label>
        </div>
        <div class="steps1-container7 thq-card">
          <img
            :alt="step4ImageAlt"
            :src="step4ImageSrc"
            class="steps1-image4 thq-img-ratio-1-1"
          />
          <h2 class="thq-heading-2">{{ step4Title }}</h2>
          <span class="steps1-text20 thq-body-small">{{ step4Description }}</span>
          <label class="steps1-text21 thq-heading-3">04</label>
        </div>
      </div>
    </div>
    <app-timeline4></app-timeline4>
  </div>
</template>

<script>
import AppTimeline4 from './timeline4'

export default {
  name: 'Steps1',
  props: {
    step4ImageAlt: {
      type: String,
      default: 'Breakthrough Information Image',
    },
    step1ImageSrc: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    step3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1613145221718-b933d69ef480?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxOTE2NTM3M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    step1ImageAlt: {
      type: String,
      default: 'Book an Appointment Image',
    },
    step2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1709127347874-3f4674be5bc8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxOTE2NTM3M3w&ixlib=rb-4.0.3&q=80&w=1080',
    },
    step1Title: {
      type: String,
      default: 'Book an Appointment',
    },
    step3Description: {
      type: String,
      default:
        'Use our symptom checker tool to assess your symptoms and get recommendations for next steps.',
    },
    step3ImageAlt: {
      type: String,
      default: 'Symptom Checker Image',
    },
    step4ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1548979833-0e583e619a76?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTcxOTE2NTM3NHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    step3Title: {
      type: String,
      default: 'Symptom Checker',
    },
    step4Title: {
      type: String,
      default: 'Breakthrough Information',
    },
    step2Alt: {
      type: String,
      default: 'Specialty Tests Image',
    },
    step2Description: {
      type: String,
      default:
        'Access a wide range of specialty tests to get a comprehensive view of your health condition.',
    },
    step2Title: {
      type: String,
      default: 'Specialty Tests',
    },
    step4Description: {
      type: String,
      default:
        'Stay informed with the latest breakthroughs and developments in the medical field.',
    },
    step1Description: {
      type: String,
      default:
        'Easily schedule a virtual appointment with a doctor specialized in the medical area you need.',
    },
  },
  components: {
    AppTimeline4,
  },
}
</script>

<style scoped>
.steps1-container1 {
  width: 100%;
  height: auto;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.steps1-max-width {
  gap: var(--dl-space-space-unit);
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.steps1-container2 {
  gap: var(--dl-space-space-unit);
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.steps1-container3 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
 
.steps1-image1 {
  width: var(--dl-size-size-large);
  height: var(--dl-size-size-large);
}
 
.steps1-text11 {
  text-align: center;
}
 
.steps1-text12 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
 
.steps1-container4 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  border-radius: var(--dl-radius-radius-cardradius);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
 
.steps1-image2 {
  width: var(--dl-size-size-large);
  height: var(--dl-size-size-large);
}
 
.steps1-text14 {
  text-align: center;
}
 
.steps1-text15 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
 
.steps1-container5 {
  gap: var(--dl-space-space-unit);
  flex: 1;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.steps1-container6 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  border-radius: var(--dl-radius-radius-cardradius);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
 
.steps1-image3 {
  width: var(--dl-size-size-large);
  height: var(--dl-size-size-large);
}
 
.steps1-text17 {
  text-align: center;
}
 
.steps1-text18 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
 
.steps1-container7 {
  flex: 1;
  display: flex;
  position: relative;
  align-items: center;
  border-radius: var(--dl-radius-radius-cardradius);
  flex-direction: column;
  justify-content: center;
  background-color: var(--dl-color-theme-neutral-light);
}
 
.steps1-image4 {
  width: var(--dl-size-size-large);
  height: var(--dl-size-size-large);
}
 
.steps1-text20 {
  text-align: center;
}
 
.steps1-text21 {
  top: var(--dl-space-space-unit);
  right: var(--dl-space-space-unit);
  position: absolute;
  font-size: 40px;
  font-style: normal;
  font-weight: 700;
}
 
@media(max-width: 991px) {
  .steps1-max-width {
    flex-direction: column;
  }
}
 
@media(max-width: 767px) {
  .steps1-container2 {
    flex-direction: column;
  }
  .steps1-container3 {
    width: 100%;
  }
  .steps1-container4 {
    width: 100%;
  }
  .steps1-container5 {
    flex-direction: column;
  }
  .steps1-container6 {
    width: 100%;
  }
  .steps1-container7 {
    width: 100%;
  }
}
</style>
