# Krea2 turbo uncensored LoRA survey

Checkpoint: Krea2_turbo_uncensored_edit_v1.1-fp8_scaled, 10 steps, cfg 1, euler/simple, 1024x1536, seed 101 unless noted.
Character: Rexa, adult female orc beastmaster, nude studio portrait unless the LoRA needs a sex pose.
Control portrait: out/base_portrait/s101.png — clean cel orc, short closed slit, hands and feet intact, tooth necklace the model invented.

Excluded, not Krea2 weights (wrong keys, would not apply on this UNET):
- H3 / MiniMax video LoRAs: fasth3_vsa_gate, MiniMaxH3_Ref2V_PBRStyle, minimax_h3_turbo_*, MysticXXX, polyhedron_minimax, riding_pose_H3, SexGod-NaughtyTimes
- Qwen-Image-2 LoRAs (transformer_blocks / transformer.* keys): NSFW_Qwen_Lora, NSFW_Qwen_TheseAlpacas_v2, qwen21_nude_edit, qwen21_penis_coachbate, qwen21_uncut_penis_coachbate, qwen21_vagina, Qwen viggle turbo 4-step and 6-step
- Speed LoRAs for the deleted rawgirl checkpoint, forbidden on this turbo file: krea2_turbo_distill_r128, krea2_raw_distill_x2_comfy

## Verdicts

- Disney_Animation_Style_Krea2: USE lightly. 0.82 is almost the base plus fur cuffs and clawed toes. 1.0 is the clearer take (t2): cleaner cel, extra fur bracers and fur boots, claws, slit stays short. Does not ruin the orc. Not required — the base already looks like this.
- Pixar_Disney_3D_Style: SKIP for this character. On the lineart prompt at 0.9 it barely changes; at 1.3 it cute-ifies (big eyes, tusks fade). With a 3D prompt at 1.1 (t3) it becomes a doll-like 3D cutie and drops the tusks. The same 3D prompt with no LoRA (pixar_ctrl) is a better 3D orc and keeps the tusks. The LoRA is what makes her a cutie.
- PornMaster_Uncensored_Krea2_V1: SKIP. 0.4 matches the base. 0.9 (t2) adds fur gauntlets, bear-leg boots and a pubic tuft. No anatomy gain.
- snofs_krea_v1_4_256_lora: SKIP. 0.4 matches the base. 1.0 (t2) adds a black mark over the crotch and blotchy paint. No detail gain.
- KNP_V2_copy_copy: SKIP. 0.7 matches the base. 1.25 makes the hood more alive, softens the body, adds a crotch tuft. The old "separate bear head" failure is starting, and there is no benefit.
- Incase_Krea_v2_epoch_10: DO NOT USE. 0.8 (t1) turns arms and legs into bear fur and paws and adds a pubic bush. 0.35 is invisible. The strength that does anything ruins the body.
- krea2_identity_edit_v1_2: DO NOT USE on this checkpoint. 1.0 is pure color noise (t1). 0.25 is just the base plus fur cuffs. This LoRA was for the deleted rawgirl edit.

Oral control: base_oral failed (penis not in the mouth, fur shorts). base_oral_t2 is the real control: nude, tongue on a green shaft, not sealed, not deep.

- blowjob_krea2_v1: SKIP. 0.7 and 1.0 stay a lick with a pink head. Same as the base. t1 added a melted hand on the shaft.
- deepthroat_krea2_v1: SKIP. 0.8 and a tight crop at 1.15 still leave the shaft outside, tongue out, drool. The tight crop also grew a live bear face.
- POV_Sideview_Deepthroat: SKIP. Two tries, still a lick, not POV, not deep. Adds fur.
- k_giantdeepthroat: SITUATIONAL. At 0.8 (t1) the shaft actually enters her mouth, with drool, but the penis is scaly and green. At 0.55 it falls back to a lick. Use only at about 0.8 and accept the scales.
- k_inverteddeepthroat: SITUATIONAL. With the bear hood the face merges into a second bear (t1), and the no-LoRA control of that prompt does it too. Without the hood (t2) the orc's penis reaches her mouth while she lies head-off the bench. The same prompt with no LoRA (ctrl2) puts the penis on her chest instead. Use it for that pose, and do not wear an animal hood.
- k_mountedfellatio: DO NOT USE. She never sits facing his groin. t2 grows the penis out of his chest. t3 puts a penis in his mouth.
- K_POVreversefellatio: DO NOT USE. t1 inserts a live bear between her face and her butt. t2 without the hood is a POV lick, but her body is folded so the butt sits above her head with no torso.
- k_cumstringsultimate: MILD. At 1.1 (t2) several white strings reach her tongue. The same prompt with no LoRA is one drip. It also dresses her in bone armor, but the no-LoRA shot did that too. Use only if you want the strings.
- k_strappadobj: SKIP. Three tries never put both wrists behind her back. Rope floats off the frame or ties one forearm in front. Oral stays a lick.

Anal control: base_anal drew a pink fist, not a penis. base_anal_t2 is the real control: a pink penis hangs in the corner and never touches her. The slit stays short and closed. No insertion without a LoRA.

- LoRAAnalSexKrea2: SKIP on this checkpoint for placement. At 0.8 (t1, same prompt and seed as the control) the penis still floats in the corner. At 1.15 on a tight hip crop (t2) the shaft comes up from below and meets the body, which is the old lap-from-below failure, not a shaft coming down into the upper hole. It does not fix anal on turbo.
- AAA_NM_AmtAnal_Krea2: SKIP. At 0.8 (t1) the penis floats in the corner, same miss as the control. At 1.15 on a hip crop (t2) the penis lies on her buttock, the anus is empty, an extra hand grips the cheek, and the slit is drawn open. No insertion.
- Krea2penetrationcontrol1500step: DO NOT USE. Trigger Pen_ at 0.8 (t1) leaves the penis in the corner, same as the control. At 1.1 on a hip crop (t2) the penis still floats, and rectangular skin patches appear on her lower back. It does not control penetration.
- anal_insertion_krea2: DO NOT USE. Trigger anal at 0.8 (t1) drifts toward a veiny semi-real penis and a white floor, and the penis still floats. At 0.55 on a hip crop (t2) the head presses into a buttock, a second shaft melts into a leg, and a fur tail hangs over the slit. It never enters the anus.
- anal_helper_krea2_loraholic: SKIP. At 0.9 (t1) it matches the control: penis in the corner, no contact. At 1.2 on a hip crop (t2) the penis still floats and the anus is empty. It does not help placement.
- k_blackanal: SKIP. Trigger 4nal at 0.8 (t1) matches the control, penis in the corner. At 1.1 on a hip crop (t2) the penis still floats, the anus is empty, and bone straps appear on her ribs. No anal.
- k_bulldoganal: SKIP. Trigger b0lld0g. t1 and t2 stay on hands and knees with a green penis that does not enter. t3 and t4 get her on her back with feet near her head, but the penis rests on the slit and t4 draws it open. The same prompt with no LoRA (ctrl, seed 110) is a cleaner folded pose and the penis still sits on the crotch. The LoRA is not what creates the pose, and it does not give anal.
- ANAL_ONSIDE_v10: SITUATIONAL. Trigger onsideanal at 0.85 (t1) puts a green shaft against her butt from behind while she sits on her side. The same prompt with no LoRA shows the orc but no penis. t2 at 0.9 makes the penis pink and presses the head into the cheek while the anus stays empty. Use it only for the side-lying partner, and do not expect a clean insertion.
- k_doggyadrianoanal: DO NOT USE. At 0.8 (t1) the orc and the penis disappear and she just kneels. At 1.05 (t2) a green orc stands behind her while a second body under her supplies the penis. Two partners. It does not draw one man in doggy.
- K_doggystyledoubleanal: DO NOT USE. At 0.85 (t1) it does draw two pink penises, but they float under her butt and the anus is empty. At 1.05 (t2) both shafts float beside her hip, a belt appears, and nothing enters. Count without insertion.
- krea2-doubleanal-step4000-k3nk: SITUATIONAL. At 0.8 (t1) there are zero penises and a fur flap over the hip. At 1.15 (t2) two shafts meet the hole but her skin turns yellow-green and the braids vanish. At 1.0 (t3) tan skin, braids and paint stay, and two pink shafts sit together against the anus. The same prompt with no LoRA draws no penises. Use about 1.0 when you need two shafts. They touch the hole; they do not bury.
- anal_gape_krea_2_v1: SKIP on this checkpoint. g4pe at 0.7 (t1) is a normal closed anus. At 1.05 (t2) it is still a small pucker. g4pe_krea2_v1 at 1.15 (t3) stays a small star and adds a fur top and a spiked bracer. It does not open a round hole on turbo.
- assgape_woman_krea2_epoch_20: SKIP. At 0.9 (t1) the anus is a normal pucker. At 1.2 on a tight crop (t2) it is a slightly darker star, not a wide round hole, and a hand is half out of frame. No gain over asking for a close-up.
- spread_anal_krea2_3282804_epoch_10: DO NOT USE. At 0.85 (t1) her hands rest on her cheeks but the anus stays a small star. At 1.15 (t2) the camera flips to the front, the hole is a wrinkled star, the slit is drawn in detail, and extra hands appear on her belly.
- Full_Nelson_Reverse_Cowgirl_Anal_V1: USE for the legs-up front hold. At 0.8 with the hood (t1) she faces the camera with legs spread and a green penis at the crotch, plus a necklace and fur. At 0.9 without the hood (t2) her hands are behind her head, legs are up, and a pink penis meets the slit. The same prompt with no LoRA (ctrl) stands her upright with no penis. It is not a textbook full nelson and the shaft reads as the slit, not a separate anus. Still the only LoRA here that creates this pose.
- k_adrianomissioanry2: SKIP. At 0.85 (t1) she reclines on top of him and the penis is outside. At 1.05 (t2) she is on her back and the penis is visible, but he kneels beside her and a pubic tuft appears. The same prompt with no LoRA puts him clearly on top of her. The LoRA is not the missionary.
- plug_te: DO NOT USE. No trigger in the file. At 0.9 (t1) a black ring plug sits in the anus, and the same prompt with no LoRA (ctrl) already draws that plug. At 1.2 on a jeweled-plug close-up (t2) the jewel appears, but both hands grow out of the thighs and the slit is drawn long. The same close-up with no LoRA (ctrl2) keeps the jewel, real hands, and a shorter slit. The LoRA is not the plug, and the strength that changes the picture melts the limbs.
- K_bdsmarmsonlegs: SKIP. Trigger bd5m. At 0.85 (t1) the rope is only on the ankles and both hands are free behind her hips. At 1.1 (t2) each hand sits on an ankle with rope around the wrist, plus a pubic tuft and a more open slit. The same prompt with no LoRA (ctrl) already ties each wrist to the matching ankle and keeps a shorter slit. The LoRA is not the bind.
- K_suspendedreversecowggirl: SKIP. At 0.85 (t1) she faces the camera, held in the air by the thighs, with a green penis below. A third hand sits on her shoulder and a pubic tuft appears. The same prompt with no LoRA (ctrl) already lifts her the same way, with a pinker shaft and no extra hand. The LoRA is not the pose.
- k_piledriver: USE for the folded pose. Trigger p1ledriver. At 0.85 (t1, seed 101) she is on her back with both legs up and a green orc over her shoulders, penis pointing down. An extra green hand rests on her hip. The same prompt with no LoRA (ctrl) leaves her flat on her back, dresses the man in a fur kilt, and draws no penis. At 1.0 (t2, seed 108) the fold is clearer, he holds both ankles, and the pink penis points straight down between her thighs. His head is cropped and the hands on her calves look fused. Use about 1.0 when you need the fold. The prompt alone does not make it.
