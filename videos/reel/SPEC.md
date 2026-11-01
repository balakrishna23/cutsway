# SPEC: Cutsway reel, The Raw Pile (15 s)

GOAL:    a gaming creator or podcaster feels "my hours of footage can be cut, fast" and remembers cutsway.com.
OUTPUT:  HyperFrames, 1080 x 1920, 30 fps. Silent cut (sound added later on request).
TIME:    15 s x 30 = 450 frames.

LOOK:    ground Night #07070a, with three low radial glows on the bottom edge (blue #1c4cdd at 34% bottom-left,
         olive #6b5d12 at 30% bottom-centre, red #fb3b27 at 26% bottom-right), each 900-1100 px wide.
         Stars: 90 dots at 1-2 px, 8-30% Paper.
         Display: Archivo, width 125, weight 900, upper case, tracking -0.012em, line height 0.87.
         Hero 200-236 px, second line 104-120 px. Support: Archivo width 100, weight 600, 48-56 px.
         Accent rules: Yellow #fddf4b marks the one word that matters per shot; Red #fb3b27 belongs to the cut;
         the spectrum lives only in the logo, the light sweep and the 4 px foot line under the URL.
OBJECTS: raw clips are video frames: 16:9 cards with a 3 px dark bezel, a filename label ("CLIP_0412.mp4"),
         and one of four thumbnails (gameplay with a HUD bar, a two-person podcast, a LOADING screen,
         an editor timeline), all desaturated. Keepers regain colour.
         The razor is a 6 px line, Red core with a 22 px Paper-white glow, crossing the full frame.
MOTION:  arrive expo.out / power4.out; camera power2.inOut; exits and fly-ins power3.in.
         No bounce, no elastic. Titles land and hold dead still. Words stagger 0.07 s.
SHOTS:
  0-60     THE PILE. 150 grey clips tumble (3-14 deg/s spin, 6-24 px/s drift), camera push 1.00 -> 1.05.
           "YOUR / RAW PILE." already on screen at frame 0 (hook), Paper 228 px, centred at y 760-1000.
  60-64    RAZOR 1 crosses left -> right in 4 frames. Every clip it crosses splits in two.
  64-150   THE CUT. Rejects (86%) flush red, edges burn orange #fc8020, break into embers rising 120-260 px.
           Second razor right -> left at frame 78; "WE / CUT IT." lands on it, IT in Yellow.
           Keepers (21 clips) regain colour.
  138-150  Keepers accelerate into the frame centre (power3.in) and shrink: cut on the fastest frame.
  150-279  THE KEEPERS. Three cards, 900 x 330, stacked at y 330 / 735 / 1140 (top edges):
           GAMING (frame 150, scales up from the centre), SHORTS (frame 186, whip from the right),
           PODCASTS (frame 222, whip from the left; real photo assets/mic-2.jpg).
           Frames 261-279: the three cards collapse into one 900 x 20 bar at y 1010 (morph).
  279-348  THE SPEED. The bar becomes a progress bar that fills with Yellow while a timer counts 00:00 -> 12:00.
           "SHORTS BACK IN" 112 px Paper, "12 HOURS." 236 px with 12 in Yellow.
  348-450  THE LOGO. The full bar shrinks into the CUTSWAY wordmark (900 px wide), which fills left -> right
           over a 10% grey ghost like an export bar; one light sweep at frame 384.
           "cutsway.com" 100 px Paper, 4 px spectrum foot line; "WhatsApp +91 62813 01476" 52 px Soft.
           Holds still from frame 396 to 450 (1.8 s fully still, 2.6 s readable).
BANNED:  slow fades, bounce, floating or breathing titles, glow on type, spectrum on text,
         stock icons, other brands' logos, words below y 1330, more than 6 words readable at once.
QA:      frames 0, 30, 62, 90, 120, 145, 152, 200, 240, 270, 300, 340, 370, 420, 449.
