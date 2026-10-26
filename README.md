# BetterClicks
Optimizes and corrects 1-frame clicks. If the mod detects that a click lands on a frame with an obstacle, it delays the action to the following safe frame to prevent an instant collision. Fine-tunes input accuracy and avoids unintended deaths from frame desync.

A Geode mod designed to correct click precision and prevent accidental failures caused by micro-frame mismatches.

How it works:

If you register a 1-frame click on a frame that contains a hazard/obstacle (spike, block edge, etc.), the mod detects the collision risk on that exact frame and automatically delays the click input to the next safe frame. This ensures your input is only processed when it won't trigger an immediate death due to same-frame hitboxes.

Key Features:

1-Frame Input Adjustment: Automatically evaluates single-frame inputs.

Adaptive Obstacle Delay: Postpones the click execution if a fatal collision is detected in the current frame.

Precision Safety: Prevents lost attempts caused by input polling rates or micro-stutters.
