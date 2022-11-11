The actions a character can do while in their turn of battle.

These moves contain the following information to determine what actions it executes:

* Name;
    What the move is called. It'll show up on various spots of the UI.

* Description;
    An human readable explanation of what the move actually does.

* Power;
    The effectiveness of the move. It's used to both determine how much damage the move will inflict, or how much this move will heal for, depending on the [[Move Target]].

* Effect;
     Certain moves can apply [[Battle Effects]] to the target, depending on the probability described on the apply chance.

* Apply chance;
    A integer number from 0 to 100, representing the chance of the move applying the [[Battle Effects]] on the target.

* Cost;
    The energy needed from the character to execute this move. If the character didn't roll high enough to use this move, it'll be faded and not selectable from the list.

* Accuracy;
    An integer number from 0 to 100, representing the chance of the move hitting and doing its action.

* Type;
    The [[Move Type]] determines the effectiveness of the action, applying a multiplier to the [[Moves Power]].

* Target;
    The [[Move Target]] is responsible for determining which battle characters will be affected by the action.

* Extra actions;
    Extra Actions are used on complex moves that execute multiple actions at once.






