The files in this folder are used for the horse sprites in the recreation of the stables. A document for tracking the progress of stable sprite recreation can be found [here](https://docs.google.com/spreadsheets/d/1QgKKvr9kadI8oqGTSF6VBwhwczXinlrxPxuNb-B3axg/edit?usp=sharing) and a guide for recreating sprites can be found [here](https://docs.google.com/document/d/1kyHGYg63570dLtasXB3KsgDX0GgGryqy3tYj9TxincE/edit?usp=sharing)

## Folders
- [Cached Horses](https://github.com/Bella-Sara-Archival-Team/besaspine/tree/main/neocities/phasergames/stables/Cached%20Stable%20Horses) are the horses that have been extracted from cached stable horse files. This is done by opening the file in jpexs and exporting the relevant sprite images. The .swf file for the horse is also included in their folder for quick reference.
- [Other Cached Horses](https://github.com/Bella-Sara-Archival-Team/besaspine/tree/main/neocities/phasergames/stables/Other%20Cached%20Horses) are horses that have been extracted from non-stable files such as the storybook or cloud jumper
- [Recreated Horses](https://github.com/Bella-Sara-Archival-Team/besaspine/tree/main/neocities/phasergames/stables/Recreated%20Horses) are horses that have been recreated from screenshots (usually found on the wiki.gg). The horses in this folder often include a .kra (Krita) file which may be used as a starting point for recreating other horses. Peter's file has also been exported as a .psd file which should work in other programs if needed.
- [Dirt Layer](https://github.com/Bella-Sara-Archival-Team/besaspine/tree/main/neocities/phasergames/stables/Dirt%20Layer) is for the dirt layer sprites which are used to make the horse appear dirty before brushing them. These aren't exactly horse sprites, but they reuse the same animations
- [Dress Up Horse](https://github.com/Bella-Sara-Archival-Team/besaspine/tree/main/neocities/phasergames/stables/Dress%20Up%20Horse) includes the files for the dress up horse. Note that this is a VERY complex file since it includes all the different dress up options and is split into parts for animation

## Horse Parts
Each set of horse parts uses a consistent naming scheme so it's easier to reuse existing spine files when adding new horses. The following file names should be used whenever possible:
- All.png - the entire horse (shows where each part should go)
- Apple.png - the apple (or other treat) image. This can be copied from Peter's folder for land and air horses, or from Nori's folder for water horses if needed
- Body.png
- Ear.png
- Eye1.png-Eye5.png - the different frames of the bink animation. These can often be copied from a horse with similar eyes if needed
- Forelock.png
- Head.png
- HeadJaw.png - the lower jaw with the inner portion of the mouth
- HeadUpper.png - the head with the lower jaw hidden. Note that this sprite should NOT include the eye because the eye blink animation is separate
- LowerFL.png - the lower half of the front left leg. May also include the hoof
- LowerFR.png - the lower half of the front right leg. May also include the hoof
- LowerHL.png - the lower half of the hind left leg. May also include the hoof
- LowerHR.png - the lower half of the hind right leg. May also include the hoof
- Mane.png
- Neck.png
- Shadow1.png - the horse's shadow. This can be copied from Peter's folder for land and air horses.
- Tail.png
- UpperFL.png - the upper half of the front left leg
- UpperFR.png - the upper half of the front right leg
- UpperHL.png - the upper half of the hind left leg
- UpperHL.png - the upper half of the hind right leg
- Bubbles (folder) - includes the frames of the bubble animation for water horses. This can be copied from Nori's folder if needed
- *HoofFL.png, HoofFR.png, HoofHL.png, HoofHR.png* - the hoof for the indicated leg. Is not needed if merged with the lower leg sprite
- *WingL.png, WingR.png* - the wings for horses with wings
- *Tail.png, Tail2.png, Tail3.png, TailFin.png* - the tail sections for a hippocampus

Any other additional images (e.g. for a bridle, saddle, harness, cloak, &c.) can be named however makes sense. Note that any accessories do need to be isolated if they are over the head, neck, body, upper front left, or upper back left leg since the dirt layer needs to appear over the body but under the accessory. Certain parts (such as sparkles, reins or tassles) may also need to be separated so they may be animated with their own movement.
