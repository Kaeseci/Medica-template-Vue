<template>
  <div class="thq-section-padding">
    <div class="timeline4-max-width thq-section-max-width">
      <div class="timeline4-container11">
        <h2 class="thq-heading-2">{{ title1 }}</h2>
        <span class="timeline4-text11 thq-body-small">{{ content1 }}</span>
        <div class="timeline4-container12">
          <button type="button" class="thq-button-filled">{{ action1 }}</button>
          <button type="button" class="thq-button-outline">{{ action2 }}</button>
        </div>
      </div>
      <div class="timeline4-timeline-container">
        <div class="timeline4-step1">
          <div class="timeline4-container13">
            <div class="timeline4-container14"></div>
            <div class="timeline4-progress01"></div>
          </div>
          <div class="timeline4-container15">
            <h3 class="thq-heading-3">{{ date1 }}</h3>
            <h3 class="timeline4-text13 thq-heading-3">{{ card1Heading }}</h3>
            <span class="thq-body-small">{{ card1Content }}</span>
            <div class="timeline4-container16">
              <button type="button" class="thq-button-filled">
                {{ card1Action1 }}
              </button>
              <button type="button" class="thq-button-outline">
                {{ card1Action2 }}
              </button>
            </div>
          </div>
        </div>
        <div class="timeline4-step2">
          <div class="timeline4-container17">
            <div class="timeline4-container18"></div>
            <div class="timeline4-progress02"></div>
          </div>
        </div>
        <div class="timeline4-step3">
          <div class="timeline4-container19">
            <div class="timeline4-container20"></div>
            <div class="timeline4-progress03"></div>
          </div>
          <div class="timeline4-container21">
            <h3 class="thq-heading-3">{{ date3 }}</h3>
            <h3 class="timeline4-text16 thq-heading-3">{{ card3Heading }}</h3>
            <span class="thq-body-small">{{ card3Content }}</span>
            <div class="timeline4-container22">
              <button type="button" class="thq-button-filled">
                {{ card3Action1 }}
              </button>
              <button type="button" class="thq-button-outline">
                {{ card3Action2 }}
              </button>
            </div>
          </div>
        </div>
        <div class="timeline4-step4">
          <div class="timeline4-container23">
            <div class="timeline4-container24"></div>
            <div class="timeline4-progress04"></div>
          </div>
          <div class="timeline4-container25">
            <h3 class="thq-heading-3">{{ date4 }}</h3>
            <h3 class="timeline4-text19 thq-heading-3">{{ card4Heading }}</h3>
            <span class="thq-body-small">{{ card4Content }}</span>
            <div class="timeline4-container26">
              <button type="button" class="thq-button-filled">
                {{ card4Action1 }}
              </button>
              <button type="button" class="thq-button-outline">
                {{ card4Action2 }}
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Timeline4',
  props: {
    card3Content: {
      type: String,
      default:
        'Schedule a virtual appointment with leading cardiologists to discuss your heart health and receive personalized recommendations.',
    },
    date1: {
      type: String,
      default: '2022-01-15',
    },
    title1: {
      type: String,
      default: 'Medical Breakthroughs',
    },
    action1: {
      type: String,
      default: 'Read More',
    },
    card3Heading: {
      type: String,
      default: 'Consultation with Top Cardiologists Available',
    },
    card4Heading: {
      type: String,
      default: 'Innovative Cancer Treatment Center Opens',
    },
    action2: {
      type: String,
      default: 'Explore Tests',
    },
    card1Heading: {
      type: String,
      default: 'New Treatment Discovered for Rare Disease',
    },
    card1Action1: {
      type: String,
      default: 'Learn More',
    },
    card3Action1: {
      type: String,
      default: 'Meet the Specialists',
    },
    card4Action2: {
      type: String,
      default: 'Find a Doctor',
    },
    card1Action2: {
      type: String,
      default: 'Watch Video',
    },
    date4: {
      type: String,
      default: '2022-04-10',
    },
    card4Action1: {
      type: String,
      default: 'Learn More',
    },
    date3: {
      type: String,
      default: '2022-03-20',
    },
    card3Action2: {
      type: String,
      default: 'Book Appointment',
    },
    card1Content: {
      type: String,
      default:
        'Researchers have found a groundbreaking treatment for a rare genetic disorder, offering hope to patients worldwide.',
    },
    card4Content: {
      type: String,
      default:
        'Explore the newest cancer treatment center in your area, offering state-of-the-art therapies and expert oncologists.',
    },
    content1: {
      type: String,
      default: 'Entspannt ankommen',
    },
  },
}
</script>

<style scoped>
.timeline4-max-width {
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
}
 
.timeline4-container11 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.timeline4-text11 {
  text-align: left;
}
 
.timeline4-container12 {
  gap: var(--dl-space-space-unit);
  flex: 0 0 auto;
  width: auto;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
 
.timeline4-timeline-container {
  flex: 1;
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
 
.timeline4-step1 {
  display: flex;
  position: relative;
  justify-content: center;
}
 
.timeline4-container13 {
  flex: 1;
  left: var(--dl-space-space-halfunit);
  height: 100%;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.timeline4-container14 {
  width: 12px;
  height: 12px;
  margin: var(--dl-space-space-halfunit);
  border-radius: var(--dl-radius-radius-round);
  background-color: #000000;
}
 
.timeline4-progress01 {
  width: auto;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #000000;
}
 
.timeline4-container15 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-left: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  justify-content: flex-start;
}
 
.timeline4-text13 {
  text-align: left;
}
 
.timeline4-container16 {
  gap: var(--dl-space-space-unit);
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
}
 
.timeline4-step2 {
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
 
.timeline4-container17 {
  flex: 1;
  left: var(--dl-space-space-halfunit);
  width: auto;
  height: 100%;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.timeline4-container18 {
  width: 12px;
  height: 12px;
  margin: var(--dl-space-space-halfunit);
  border-radius: var(--dl-radius-radius-round);
  background-color: #000000;
}
 
.timeline4-progress02 {
  width: auto;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #000000;
}
 
.timeline4-step3 {
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
 
.timeline4-container19 {
  flex: 1;
  left: var(--dl-space-space-halfunit);
  width: auto;
  height: 100%;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.timeline4-container20 {
  width: 12px;
  height: 12px;
  margin: var(--dl-space-space-halfunit);
  border-radius: var(--dl-radius-radius-round);
  background-color: #000000;
}
 
.timeline4-progress03 {
  width: auto;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #000000;
}
 
.timeline4-container21 {
  gap: var(--dl-space-space-unit);
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-left: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  justify-content: flex-start;
}
 
.timeline4-text16 {
  text-align: left;
}
 
.timeline4-container22 {
  gap: var(--dl-space-space-unit);
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
}
 
.timeline4-step4 {
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
 
.timeline4-container23 {
  flex: 1;
  left: var(--dl-space-space-halfunit);
  width: auto;
  height: 100%;
  display: flex;
  position: absolute;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
 
.timeline4-container24 {
  width: 12px;
  height: 12px;
  margin: var(--dl-space-space-halfunit);
  border-radius: var(--dl-radius-radius-round);
  background-color: #000000;
}
 
.timeline4-progress04 {
  width: auto;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #000000;
}
 
.timeline4-container25 {
  gap: var(--dl-space-space-unit);
  width: auto;
  display: flex;
  align-items: flex-start;
  padding-left: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
  justify-content: flex-start;
}
 
.timeline4-text19 {
  text-align: left;
}
 
.timeline4-container26 {
  gap: var(--dl-space-space-unit);
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  flex-direction: row;
}
 
@media(max-width: 991px) {
  .timeline4-max-width {
    gap: var(--dl-space-space-twounits);
  }
}
 
@media(max-width: 767px) {
  .timeline4-max-width {
    flex-direction: column;
  }
  .timeline4-text11 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .timeline4-text13 {
    text-align: left;
  }
  .timeline4-text16 {
    text-align: left;
  }
  .timeline4-text19 {
    text-align: left;
  }
}
 
@media(max-width: 479px) {
  .timeline4-container11 {
    gap: var(--dl-space-space-unit);
  }
  .timeline4-container12 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .timeline4-timeline-container {
    width: 100%;
  }
  .timeline4-container16 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .timeline4-container22 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
  .timeline4-container26 {
    width: 100%;
    align-items: stretch;
    flex-direction: column;
  }
}
</style>
