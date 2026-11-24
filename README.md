# Svayam-
Empowering Independence Through Technology 
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Manrope:wght@500;600;700;800&display=swap');

:root {
  font-family: "DM Sans", sans-serif;
  color: #edf3f8;
  background: #0b1220;
  font-synthesis: none;
  text-rendering: optimizeLegibility;
}
* { box-sizing: border-box; }
body { margin: 0; min-width: 320px; background: radial-gradient(circle at 80% 0%, #183b45 0, #0b1220 38rem); }
.shell { max-width: 1100px; margin: 0 auto; padding: 28px 28px 36px; }
.topbar { display: flex; align-items: center; gap: 12px; border-bottom: 1px solid #243244; padding-bottom: 22px; }
.brand-mark { width: 42px; height: 42px; display: grid; place-items: center; border-radius: 13px; background: #8de0c4; color: #09251f; font: 800 24px Manrope; }
.brand { font: 800 17px Manrope; letter-spacing: 2px; }
.brand-subtitle, .eyebrow { font-size: 10px; letter-spacing: 1.8px; color: #8de0c4; font-weight: 700; }
.status { margin-left: auto; border: 1px solid #41665e; color: #9be4c8; padding: 7px 11px; border-radius: 30px; font-size: 10px; letter-spacing: 1px; }
.hero { padding: 62px 0 38px; }
h1, h2 { font-family: Manrope, sans-serif; margin: 10px 0; }
h1 { font-size: clamp(36px, 6vw, 62px); line-height: 1.08; letter-spacing: -2px; }
h1 span { color: #8de0c4; }
.intro, .muted { color: #a5b3c3; line-height: 1.7; }
.intro { max-width: 610px; font-size: 16px; }
.upload-panel, .insight-panel, .empty-state { background: #131f2e; border: 1px solid #29394a; border-radius: 18px; padding: 24px; }
.upload-panel { display: flex; align-items: center; justify-content: space-between; gap: 20px; flex-wrap: wrap; }
.upload-panel h2, .section-heading h2, .insight-panel h2 { font-size: 22px; }
.upload-panel p { margin-bottom: 0; }
.upload-button { display: inline-block; background: #8de0c4; color: #09251f; font-weight: 700; border-radius: 10px; padding: 13px 18px; cursor: pointer; }
.upload-button input { display: none; }
.error { width: 100%; color: #ff9e9e; }
.section-heading { display: flex; justify-content: space-between; align-items: end; margin: 40px 0 16px; gap: 16px; }
.record-count { color: #a5b3c3; font-size: 12px; }
.metric-grid { display: grid; grid-template-columns: repeat(4, 1fr); gap: 14px; }
.metric-card { padding: 20px; background: #131f2e; border: 1px solid #29394a; border-radius: 15px; }
.metric-card p { margin: 0; font-size: 13px; }
.metric-value { font: 800 32px Manrope; margin-top: 14px; }
.metric-unit { color: #8de0c4; margin-top: 5px !important; }
.insight-panel { margin-top: 18px; }
.insight-panel li { color: #d2dce6; padding: 7px 0; line-height: 1.5; }
.notice { color: #a5b3c3; border-top: 1px solid #29394a; padding-top: 14px; font-size: 12px; line-height: 1.6; }
.empty-state { margin-top: 18px; text-align: center; padding: 42px 20px; }
.empty-icon { color: #8de0c4; font-size: 34px; }
.empty-state p { color: #a5b3c3; }
footer { text-align: center; color: #75879a; font-size: 11px; margin-top: 34px; }
@media (max-width: 760px) {
  .shell { padding: 18px 16px 28px; }
  .metric-grid { grid-template-columns: repeat(2, 1fr); }
  .hero { padding-top: 42px; }
  .section-heading { align-items: start; flex-direction: column; }
} 

