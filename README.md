<h1 align="center">TF2 Charge Turn Script</h1>
<p align="center">This script allows you to turn pretty sharply while using the Charge 'n Targe or Splendid Screen (and even trimp!)
<br><s>Believe it or not, Valve lied when they said they patched this in 2014.</s>
<br>You don't even need a high framerate for this script!</p>
<hr>

<h2 align="center">Installation:</h2>

<b>Note:</b> This script is incompatible with any null-canceling movement scripts (including the mastercomfig addon) because it implements its own null-canceling movement.

Copy the contents of [`chargeturn.cfg`](chargeturn.cfg) into your autoexec, and change the binds at the top as desired.
Make sure you don't have another script messing with the binds or aliases!

Advanced users can probably integrate this into their configs better, and this simply serves as a template.

<h2 align="center">How to Use:</h2>

Hold down the key that you've bound to <code>+chargeturn</code> (Shift by default) and hold your strafe keys (A and D) for left and right respectively.
You can get even faster if you also use your mouse in the direction of the turn.

TF2 is finicky sometimes and your view and turn can glitch out.
Not sure why this happens but you get better with practice.

<h2 align="center">Why does this work?</h2>

Source spaghetti idk

Using the keyboard look keys with a higher-than-default `cl_yawspeed` makes TF2 let you turn faster.

Using `m_filter` (a terrible feature that shouldn't be used otherwise) also confuses the game and lets you turn faster.

Thanks to [NotnHeavy](https://steamcommunity.com/id/NotnHeavy) and [bambr](https://steamcommunity.com/profiles/76561197974257300) for discovering most of this.

<h2 align="center">Known Issues:</h2>

Pressing the modifier key will cause your strafe/turn to instantly stop.

I was originally planning on making the script allow you to switch between turn and strafe without repressing the key, "super"-null-canceling for lack of better word, but I've yet to figure out how.

You will as a result of this sometimes notice that you just don't turn at all, which happens if you held a strafe key *before* the modifier key. You get better with practice.

Pull requests are welcome from anyone willing to help fix this.
