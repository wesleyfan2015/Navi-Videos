# Navi Movement Videos for Realistic MuJoCo Simulation

This repository is a coworker-facing motion reference for reproducing Navi as realistically as possible in MuJoCo.

## Watch the videos

Open **[the public playable video library](https://wesleyfan2015.github.io/Navi-Videos/)** to watch all **140 real MP4 videos** with their corresponding Agentech SDK commands.

GitHub's normal file view may say that an MP4 is too large to preview. Use the playable library above, or select **View raw** for an individual file.

## Contents

- `videos/movements/`: 5 translational movement videos
- `videos/actions/`: 128 Action Command videos
- `videos/athletics/`: 7 Athletic Command videos
- `videos/multi_robot/`: 1 supplemental multi-robot reference video, stored in the repository only and intentionally excluded from the website
- `videos/*/SHA256SUMS.txt`: SHA-256 integrity manifests

All videos are browser-compatible H.264 MP4 files at 1600×1200, 30 fps, full-range 4:2:0 (`yuvj420p`), with fast-start metadata. Every file was fully decoded without errors, checked for visible robot motion, transferred with exact SHA-256 verification, and then verified from its hosted GitHub Pages URL.

## Repository-only multi-robot reference

- [`Two Dogs Peeing`](videos/multi_robot/01_two_dogs_peeing.mp4): both robots complete the peeing routine and recover to standing. The 13.17-second edit removes the long idle lead-in and trailing stand time. This supplemental MP4 is not included in `index.html` or the GitHub Pages library.

## New 97-motion recording order

The first recording contributes run-order items 1–72. The follow-up recording contributes items 73–97. This table follows the exact successful SDK execution order from the “Inspect SDK features” task. Failed, timed-out, rejected, recovery-only, and prolonged idle sections are not included.

| Run order | Library item | SDK command | MP4 | Duration |
|---:|---:|---|---|---:|
| 1 | 32 | `Agentech.do_action("eager", source="extended", return_to_ready=True)` | [`32_eager.mp4`](videos/actions/32_eager.mp4) | 18.5s |
| 2 | 33 | `Agentech.do_action("rub_eyes", source="extended", return_to_ready=True)` | [`33_rub_eyes.mp4`](videos/actions/33_rub_eyes.mp4) | 7.8s |
| 3 | 34 | `Agentech.do_action("point_to_sky_left", source="extended", return_to_ready=True)` | [`34_point_to_sky_left.mp4`](videos/actions/34_point_to_sky_left.mp4) | 11.3s |
| 4 | 35 | `Agentech.do_action("point_to_sky_right", source="extended", return_to_ready=True)` | [`35_point_to_sky_right.mp4`](videos/actions/35_point_to_sky_right.mp4) | 15.1s |
| 5 | 36 | `Agentech.do_action("wait_for_praise", source="extended", return_to_ready=True)` | [`36_wait_for_praise.mp4`](videos/actions/36_wait_for_praise.mp4) | 19.4s |
| 6 | 37 | `Agentech.do_action("lucky_cat_1", source="extended", return_to_ready=True)` | [`37_lucky_cat_1.mp4`](videos/actions/37_lucky_cat_1.mp4) | 25.0s |
| 7 | 38 | `Agentech.do_action("lucky_cat_2", source="extended", return_to_ready=True)` | [`38_lucky_cat_2.mp4`](videos/actions/38_lucky_cat_2.mp4) | 2.7s |
| 8 | 39 | `Agentech.do_action("lucky_cat_3", source="extended", return_to_ready=True)` | [`39_lucky_cat_3.mp4`](videos/actions/39_lucky_cat_3.mp4) | 1.7s |
| 9 | 40 | `Agentech.do_action("drama_hearing", source="extended", return_to_ready=True)` | [`40_drama_hearing.mp4`](videos/actions/40_drama_hearing.mp4) | 14.5s |
| 10 | 41 | `Agentech.do_action("jingle", source="extended", return_to_ready=True)` | [`41_jingle.mp4`](videos/actions/41_jingle.mp4) | 6.6s |
| 11 | 42 | `Agentech.do_action("flex_muscles", source="extended", return_to_ready=True)` | [`42_flex_muscles.mp4`](videos/actions/42_flex_muscles.mp4) | 8.8s |
| 12 | 43 | `Agentech.do_action("touch_happy", source="extended", return_to_ready=True)` | [`43_touch_happy.mp4`](videos/actions/43_touch_happy.mp4) | 5.2s |
| 13 | 44 | `Agentech.do_action("good_night_wave", source="extended", return_to_ready=True)` | [`44_good_night_wave.mp4`](videos/actions/44_good_night_wave.mp4) | 6.3s |
| 14 | 45 | `Agentech.do_action("cry", source="extended", return_to_ready=True)` | [`45_cry.mp4`](videos/actions/45_cry.mp4) | 10.7s |
| 15 | 46 | `Agentech.do_action("encourage", source="extended", return_to_ready=True)` | [`46_encourage.mp4`](videos/actions/46_encourage.mp4) | 9.2s |
| 16 | 47 | `Agentech.do_action("opening_cute_dog", source="extended", return_to_ready=True)` | [`47_opening_cute_dog.mp4`](videos/actions/47_opening_cute_dog.mp4) | 12.0s |
| 17 | 48 | `Agentech.do_action("nod_head_twice", source="extended", return_to_ready=True)` | [`48_nod_head_twice.mp4`](videos/actions/48_nod_head_twice.mp4) | 6.3s |
| 18 | 49 | `Agentech.do_action("shake_head_twice", source="extended", return_to_ready=True)` | [`49_shake_head_twice.mp4`](videos/actions/49_shake_head_twice.mp4) | 13.0s |
| 19 | 50 | `Agentech.do_action("nod_with_beats", source="extended", return_to_ready=True)` | [`50_nod_with_beats.mp4`](videos/actions/50_nod_with_beats.mp4) | 3.8s |
| 20 | 51 | `Agentech.do_action("head_up_down", source="extended", return_to_ready=True)` | [`51_head_up_down.mp4`](videos/actions/51_head_up_down.mp4) | 9.8s |
| 21 | 52 | `Agentech.do_action("sniff_left_slow", source="extended", return_to_ready=True)` | [`52_sniff_left_slow.mp4`](videos/actions/52_sniff_left_slow.mp4) | 5.7s |
| 22 | 53 | `Agentech.do_action("sniff_right_slow", source="extended", return_to_ready=True)` | [`53_sniff_right_slow.mp4`](videos/actions/53_sniff_right_slow.mp4) | 11.7s |
| 23 | 54 | `Agentech.do_action("push_ahead", source="extended", return_to_ready=True)` | [`54_push_ahead.mp4`](videos/actions/54_push_ahead.mp4) | 2.3s |
| 24 | 55 | `Agentech.do_action("stick", source="extended", return_to_ready=True)` | [`55_stick.mp4`](videos/actions/55_stick.mp4) | 3.0s |
| 25 | 56 | `Agentech.do_action("sniff_ahead_3", source="extended", return_to_ready=True)` | [`56_sniff_ahead_3.mp4`](videos/actions/56_sniff_ahead_3.mp4) | 5.3s |
| 26 | 57 | `Agentech.do_action("shake_hand_2", source="extended", return_to_ready=True)` | [`57_shake_hand_2.mp4`](videos/actions/57_shake_hand_2.mp4) | 2.7s |
| 27 | 58 | `Agentech.do_action("pee_2", source="extended", return_to_ready=True)` | [`58_pee_2.mp4`](videos/actions/58_pee_2.mp4) | 5.8s |
| 28 | 59 | `Agentech.do_action("look_around_2", source="extended", return_to_ready=True)` | [`59_look_around_2.mp4`](videos/actions/59_look_around_2.mp4) | 2.7s |
| 29 | 60 | `Agentech.do_action("look_around_3", source="extended", return_to_ready=True)` | [`60_look_around_3.mp4`](videos/actions/60_look_around_3.mp4) | 2.7s |
| 30 | 61 | `Agentech.do_action("look_around_5", source="extended", return_to_ready=True)` | [`61_look_around_5.mp4`](videos/actions/61_look_around_5.mp4) | 13.8s |
| 31 | 62 | `Agentech.do_action("look_around_6", source="extended", return_to_ready=True)` | [`62_look_around_6.mp4`](videos/actions/62_look_around_6.mp4) | 4.7s |
| 32 | 63 | `Agentech.do_action("affection_7s", source="extended", return_to_ready=True)` | [`63_affection_7s.mp4`](videos/actions/63_affection_7s.mp4) | 8.2s |
| 33 | 64 | `Agentech.do_action("front_strech_without_modelscale", source="extended", return_to_ready=True)` | [`64_front_strech_without_modelscale.mp4`](videos/actions/64_front_strech_without_modelscale.mp4) | 3.5s |
| 34 | 65 | `Agentech.do_action("sway_front_back", source="extended", return_to_ready=True)` | [`65_sway_front_back.mp4`](videos/actions/65_sway_front_back.mp4) | 10.5s |
| 35 | 66 | `Agentech.do_action("step_idle", source="extended", return_to_ready=True)` | [`66_step_idle.mp4`](videos/actions/66_step_idle.mp4) | 4.7s |
| 36 | 67 | `Agentech.do_action("stand_at_attention", source="extended", return_to_ready=True)` | [`67_stand_at_attention.mp4`](videos/actions/67_stand_at_attention.mp4) | 6.0s |
| 37 | 68 | `Agentech.do_action("rear_strech", source="extended", return_to_ready=True)` | [`68_rear_strech.mp4`](videos/actions/68_rear_strech.mp4) | 5.3s |
| 38 | 69 | `Agentech.do_action("long_fart", source="extended", return_to_ready=True)` | [`69_long_fart.mp4`](videos/actions/69_long_fart.mp4) | 11.0s |
| 39 | 70 | `Agentech.do_action("short_fart", source="extended", return_to_ready=True)` | [`70_short_fart.mp4`](videos/actions/70_short_fart.mp4) | 11.5s |
| 40 | 71 | `Agentech.do_action("chatting", source="extended", return_to_ready=True)` | [`71_chatting.mp4`](videos/actions/71_chatting.mp4) | 14.7s |
| 41 | 72 | `Agentech.do_action("chatting__1", source="extended", return_to_ready=True)` | [`72_chatting__1.mp4`](videos/actions/72_chatting__1.mp4) | 6.2s |
| 42 | 73 | `Agentech.do_action("chatting__2", source="extended", return_to_ready=True)` | [`73_chatting__2.mp4`](videos/actions/73_chatting__2.mp4) | 3.3s |
| 43 | 74 | `Agentech.do_action("chatting_5s", source="extended", return_to_ready=True)` | [`74_chatting_5s.mp4`](videos/actions/74_chatting_5s.mp4) | 7.3s |
| 44 | 75 | `Agentech.do_action("thinking__1", source="extended", return_to_ready=True)` | [`75_thinking__1.mp4`](videos/actions/75_thinking__1.mp4) | 13.0s |
| 45 | 76 | `Agentech.do_action("thinking__2", source="extended", return_to_ready=True)` | [`76_thinking__2.mp4`](videos/actions/76_thinking__2.mp4) | 6.3s |
| 46 | 77 | `Agentech.do_action("talking", source="extended", return_to_ready=True)` | [`77_talking.mp4`](videos/actions/77_talking.mp4) | 4.3s |
| 47 | 78 | `Agentech.do_action("cooking_right_and_left", source="extended", return_to_ready=True)` | [`78_cooking_right_and_left.mp4`](videos/actions/78_cooking_right_and_left.mp4) | 2.3s |
| 48 | 79 | `Agentech.do_action("cooking_right_and_left_with_recovery", source="extended", return_to_ready=True)` | [`79_cooking_right_and_left_with_recovery.mp4`](videos/actions/79_cooking_right_and_left_with_recovery.mp4) | 13.5s |
| 49 | 80 | `Agentech.do_action("eating_swallow", source="extended", return_to_ready=True)` | [`80_eating_swallow.mp4`](videos/actions/80_eating_swallow.mp4) | 13.5s |
| 50 | 81 | `Agentech.do_action("eating_only", source="extended", return_to_ready=True)` | [`81_eating_only.mp4`](videos/actions/81_eating_only.mp4) | 6.8s |
| 51 | 82 | `Agentech.do_behavior("cute_2")` | [`82_cute_2.mp4`](videos/actions/82_cute_2.mp4) | 6.1s |
| 52 | 83 | `Agentech.do_behavior("very_enjoy")` | [`83_very_enjoy.mp4`](videos/actions/83_very_enjoy.mp4) | 10.2s |
| 53 | 84 | `Agentech.do_behavior("excited_2")` | [`84_excited_2.mp4`](videos/actions/84_excited_2.mp4) | 2.5s |
| 54 | 85 | `Agentech.do_behavior("confused_again")` | [`85_confused_again.mp4`](videos/actions/85_confused_again.mp4) | 10.2s |
| 55 | 86 | `Agentech.do_behavior("shake_self")` | [`86_shake_self.mp4`](videos/actions/86_shake_self.mp4) | 13.8s |
| 56 | 87 | `Agentech.do_behavior("dance_in_place")` | [`87_dance_in_place.mp4`](videos/actions/87_dance_in_place.mp4) | 7.7s |
| 57 | 88 | `Agentech.do_action("look_around_7", source="extended", return_to_ready=True)` | [`88_look_around_7.mp4`](videos/actions/88_look_around_7.mp4) | 10.0s |
| 58 | 89 | `Agentech.do_action("explore_road_yaw", source="extended", return_to_ready=True)` | [`89_explore_road_yaw.mp4`](videos/actions/89_explore_road_yaw.mp4) | 3.3s |
| 59 | 90 | `Agentech.do_action("explore_road_roll", source="extended", return_to_ready=True)` | [`90_explore_road_roll.mp4`](videos/actions/90_explore_road_roll.mp4) | 4.0s |
| 60 | 91 | `Agentech.do_action("search_env_yaw", source="extended", return_to_ready=True)` | [`91_search_env_yaw.mp4`](videos/actions/91_search_env_yaw.mp4) | 7.0s |
| 61 | 92 | `Agentech.do_action("search_env_roll", source="extended", return_to_ready=True)` | [`92_search_env_roll.mp4`](videos/actions/92_search_env_roll.mp4) | 3.0s |
| 62 | 93 | `Agentech.do_action("search_tag", source="extended", return_to_ready=True)` | [`93_search_tag.mp4`](videos/actions/93_search_tag.mp4) | 2.0s |
| 63 | 94 | `Agentech.do_action("body_tag_search", source="extended", return_to_ready=True)` | [`94_body_tag_search.mp4`](videos/actions/94_body_tag_search.mp4) | 2.5s |
| 64 | 95 | `Agentech.do_action("listen_left", source="extended", return_to_ready=True)` | [`95_listen_left.mp4`](videos/actions/95_listen_left.mp4) | 3.2s |
| 65 | 96 | `Agentech.do_action("listen_right", source="extended", return_to_ready=True)` | [`96_listen_right.mp4`](videos/actions/96_listen_right.mp4) | 2.0s |
| 66 | 97 | `Agentech.do_action("listen_right_and_left", source="extended", return_to_ready=True)` | [`97_listen_right_and_left.mp4`](videos/actions/97_listen_right_and_left.mp4) | 11.8s |
| 67 | 98 | `Agentech.do_action("tossing", source="extended", return_to_ready=True)` | [`98_tossing.mp4`](videos/actions/98_tossing.mp4) | 6.0s |
| 68 | 99 | `Agentech.do_action("tossing_left", source="extended", return_to_ready=True)` | [`99_tossing_left.mp4`](videos/actions/99_tossing_left.mp4) | 12.0s |
| 69 | 100 | `Agentech.do_action("tossing_right", source="extended", return_to_ready=True)` | [`100_tossing_right.mp4`](videos/actions/100_tossing_right.mp4) | 12.3s |
| 70 | 101 | `Agentech.do_action("explore_new_home", source="extended", return_to_ready=True)` | [`101_explore_new_home.mp4`](videos/actions/101_explore_new_home.mp4) | 2.0s |
| 71 | 102 | `Agentech.do_action("bored_half_sit", source="extended", return_to_ready=True)` | [`102_bored_half_sit.mp4`](videos/actions/102_bored_half_sit.mp4) | 3.2s |
| 72 | 103 | `Agentech.do_behavior("rest")` | [`103_rest.mp4`](videos/actions/103_rest.mp4) | 3.5s |
| 73 | 104 | `Agentech.do_action("sniff_up", source="extended", return_to_ready=True)` | [`104_sniff_up.mp4`](videos/actions/104_sniff_up.mp4) | 13.5s |
| 74 | 105 | `Agentech.do_action("bark_bark", source="extended", return_to_ready=True)` | [`105_bark_bark.mp4`](videos/actions/105_bark_bark.mp4) | 13.1s |
| 75 | 106 | `Agentech.do_action("coquetry_1", source="extended", return_to_ready=True)` | [`106_coquetry_1.mp4`](videos/actions/106_coquetry_1.mp4) | 15.6s |
| 76 | 107 | `Agentech.do_action("coquetry_2", source="extended", return_to_ready=True)` | [`107_coquetry_2.mp4`](videos/actions/107_coquetry_2.mp4) | 15.7s |
| 77 | 108 | `Agentech.do_action("look_down", source="extended", return_to_ready=True)` | [`108_look_down.mp4`](videos/actions/108_look_down.mp4) | 5.0s |
| 78 | 109 | `Agentech.do_action("snuggle_x", source="extended", return_to_ready=True)` | [`109_snuggle_x.mp4`](videos/actions/109_snuggle_x.mp4) | 2.1s |
| 79 | 110 | `Agentech.do_action("snuggle_y", source="extended", return_to_ready=True)` | [`110_snuggle_y.mp4`](videos/actions/110_snuggle_y.mp4) | 3.2s |
| 80 | 111 | `Agentech.do_action("be_sleepy", source="extended", return_to_ready=True)` | [`111_be_sleepy.mp4`](videos/actions/111_be_sleepy.mp4) | 62.6s |
| 81 | 112 | `Agentech.do_action("brush_teeth_right", source="extended", return_to_ready=True)` | [`112_brush_teeth_right.mp4`](videos/actions/112_brush_teeth_right.mp4) | 35.9s |
| 82 | 113 | `Agentech.do_action("brush_teeth_left", source="extended", return_to_ready=True)` | [`113_brush_teeth_left.mp4`](videos/actions/113_brush_teeth_left.mp4) | 35.9s |
| 83 | 114 | `Agentech.do_action("shit", source="extended", return_to_ready=True)` | [`114_shit.mp4`](videos/actions/114_shit.mp4) | 4.9s |
| 84 | 115 | `Agentech.do_action("fast_rotate", source="extended", return_to_ready=True)` | [`115_fast_rotate.mp4`](videos/actions/115_fast_rotate.mp4) | 27.0s |
| 85 | 116 | `Agentech.do_action("swim", source="extended", return_to_ready=True)` | [`116_swim.mp4`](videos/actions/116_swim.mp4) | 9.2s |
| 86 | 117 | `Agentech.do_action("joy_walk", source="extended", return_to_ready=True)` | [`117_joy_walk.mp4`](videos/actions/117_joy_walk.mp4) | 6.2s |
| 87 | 118 | `Agentech.do_action("duck_walk", source="extended", return_to_ready=True)` | [`118_duck_walk.mp4`](videos/actions/118_duck_walk.mp4) | 4.2s |
| 88 | 119 | `Agentech.do_action("step_forward", source="extended", return_to_ready=True)` | [`119_step_forward.mp4`](videos/actions/119_step_forward.mp4) | 2.2s |
| 89 | 120 | `Agentech.do_action("step_back", source="extended", return_to_ready=True)` | [`120_step_back.mp4`](videos/actions/120_step_back.mp4) | 1.7s |
| 90 | 121 | `Agentech.do_action("rotate_180", source="extended", return_to_ready=True)` | [`121_rotate_180.mp4`](videos/actions/121_rotate_180.mp4) | 3.0s |
| 91 | 122 | `Agentech.do_action("rotate__180", source="extended", return_to_ready=True)` | [`122_rotate__180.mp4`](videos/actions/122_rotate__180.mp4) | 9.7s |
| 92 | 123 | `Agentech.do_action("nod_off", source="extended", return_to_ready=True)` | [`123_nod_off.mp4`](videos/actions/123_nod_off.mp4) | 70.0s |
| 93 | 124 | `Agentech.do_action("dance_4x1500", source="extended", return_to_ready=True)` | [`124_dance_4x1500.mp4`](videos/actions/124_dance_4x1500.mp4) | 6.2s |
| 94 | 125 | `Agentech.do_action("dance_9x1000", source="extended", return_to_ready=True)` | [`125_dance_9x1000.mp4`](videos/actions/125_dance_9x1000.mp4) | 11.3s |
| 95 | 126 | `Agentech.do_action("dance_with_beatsx4", source="extended", return_to_ready=True)` | [`126_dance_with_beatsx4.mp4`](videos/actions/126_dance_with_beatsx4.mp4) | 5.5s |
| 96 | 127 | `Agentech.do_action("brush_teeth_right_start", source="extended", return_to_ready=True)` | [`127_brush_teeth_right_start.mp4`](videos/actions/127_brush_teeth_right_start.mp4) | 39.5s |
| 97 | 128 | `Agentech.do_behavior("excited")` | [`128_excited.mp4`](videos/actions/128_excited.mp4) | 4.2s |

## Recommended MuJoCo use

Use the videos to estimate phase timing, footfall order, base translation, body-height changes, roll/pitch/yaw excursions, contact transitions, landing compliance, recovery timing, and expressive pose targets. Short catalog gestures remain short when that is the complete observed motion; long routines retain all visible phases while stationary holds are trimmed.
