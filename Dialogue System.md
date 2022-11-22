The dialogue will be kept in a big text file, which is then parsed into the game.

Tags:

Dialogue
Though
Option
Move
Rotate
Emotion
Wait
Jump
End

# curiobot-diag-exampl

dialog ; curiobot-happy ; Curiobot ; Example dialogue text! ; next

thought ; null ; null ; This is a thought text

option ; curiobot-think ; Curiobot ; What will you do? ; Yes ; diag-curio-yes ; No ; diag-curio-no

move ; gameobject-altor ; 180.50 ; 70.6 ; walk

face ; gameobject-altor ; down

emotion; gameobject-altor ; surprised

jump ; gameobject-altor

wait ; 2000
script ; ChangeMusic ; bg-music-03
end
