# pitch_predictor_repo
The data file is from https://baseballsavant.mlb.com/

**Training Inputs:**
--------------------

**count:** Ball-strike count after the pitch

**previous count:** Ball-strike count before the pitch

**previous pitch:** Previous pitch type

**outs_whenup:** Number of outs in the current inning

**run difference:** Run difference between the pitcher and the batter teams before the pitch

**on_3bb:** Binary variable that determines if third base is full

**on_2bb:** Binary variable that determines if second base is full

**on_1bb:** Binary variable that determines if first base is full

**stand:** Batter handedness

**pitch_name:** Pitch type of current pitch


**Training Output:**
--------------------

**expected_pitch_name:** Next pitch type occurred after current pitch
