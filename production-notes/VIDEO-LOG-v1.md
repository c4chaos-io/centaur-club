# VIDEO LOG v1 — THE EARLY CLUB VIDEO (NOT THE FINAL FILM)

This log covers the 30 second silent v1 build of 2026-11-14, the Club's
first moving picture. It is NOT the final TRK01 film (3:12, launched
2026-11-16). Kept as production history.

---

# // VIDEO LOG v1 — CENTAUR CLUB (Club at the Edge of Eternity)
## Status: ★ DIRECTOR-APPROVED 2026-11-14 (🔥 reaction) — v1 is the
## club video of record. Repair routes (b)/(c) below NOT run; the
## named deviations stand on file beside the approval.
## Director order (2026-11-14): "No audio yet. Let's create the Suno
## audio track later. For now, animate the Centaur Club video. Make
## into live-action while maintaining our character consistency!
## Surprise me!"

## // BUILD
Three 10s live-action acts, frame-chained (each act generated from
the previous act's last frame — the snapshot-resume call errored
once with invalid args and was NOT repeated; the frame-grab chain
is the house-proven alternative), stitched hard at the seams:
- Act 1 THE DOORS — media-generation-club-act1-doors-v1-*.mp4
  Wide club, camera pushes through the dancing crowd to the booth,
  ends on a tight two-shot of the DJs.
- Act 2 THE MIX — media-generation-club-act2-mix-v1-*.mp4
  Lateral drift along the decks; becomes the pixel DJ's feature:
  both voxel hands working faders + turntable, crowd behind.
- Act 3 THE EDGE — media-generation-club-act3-edge-v1-*.mp4
  Pull-back to the wide duo shot, galaxy wall behind, crowd hands
  up, ends held wide (loop-friendly against Act 1's opening).
- Master: centaur-club-video-v1-silent.mp4 — 30.0s, 1152x768, 24fps.
  SILENT BY DESIGN: each generated act carried its own throwaway
  audio stream; all of it was stripped. The Suno track (SNOWLION
  first) gets synced later in CapCut, per the Director's order.

## // AUDIT (generated-take-audit skill: checklist, crops, frame comparison)
Whole-frame locks:
- Duo at the booth, decks + mixer, speaker stacks, crowd, star
  void: HELD in the video's own staging.
- SET FIDELITY TO THE LOCKED STILL: PARTIAL — Act 1 re-staged the
  club (galaxy wall instead of the still's single mandala, ceiling
  neon frame instead of the sign panel) instead of tracking the
  plate exactly. The still remains the poster of record; the video
  is its live-action sibling, not its twin. Director to rule.
Character locks (judged from full frames + the Act 1 end crop):
- Fluffy eyes cyan (viewer L) / magenta (viewer R), vivid in Acts
  1–2: PASS. Circuit traces, long white mane, paw on turntable:
  PASS. Dry expression: PASS in Acts 1–2.
- LOUPE DRIFT (named failure): the single brass loupe became a
  goggle pair from Act 1, and in Act 3's mid frames the lenses
  multiply (three-lens cluster) and slide over the face. Act 3's
  end wide recovers (goggles up, cyan eye visible), but Act 3 mid
  is the weakest character stretch in the cut.
- C4: featureless dark head in every sampled frame, NO facial
  features ever: PASS. Voxel dissolve: PASS Acts 1–2; Act 3 reads
  more solid mosaic, still unmistakably the pixel DJ. One glitch
  scan-line crosses his face area in Act 2 mid — reads as a glitch
  artifact, not a feature.
- Act 2 framing: Fluffy at the left edge, partial — reads as C4's
  feature act inside the 3-act structure, not an error.
- Text: no readable words added by the DJs/signage. Two minors:
  tiny "Pioneer DJ" equipment branding on the decks (Act 3), and
  abstract neon glyph shapes at the right edge (Act 3) — neither
  legible as language.
Motion (frame comparison, start/mid/end per act):
- Camera: push-in (A1) / lateral drift (A2) / pull-back + rise
  (A3) — all verified as camera motion, not subject swaps.
- Subjects: crowd arms and bodies change frame to frame; both
  DJs' hands/paws change position on the decks.
- Backdrop: the spiral changes orientation/scale across frames —
  it moves; it is not a static plate.

## // GENERATION SPEND
3 successful video generations (Acts 1–3) + 1 errored resume call
that produced nothing. No regens run. Repair routes, Director's
choice, NOT auto-run:
(a) Accept v1 as the surprise cut.
(b) Re-roll Act 3 only from Act 2's last frame with the loupe lock
    tightened (1 more generation) — the only act with a named
    character failure.
(c) Edit-lane safety cut: camera moves over the locked still
    (faces exact, far less life) as a B-version.
