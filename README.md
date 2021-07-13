# SMV-Centrare

## Logical Operators

* Path quantifier:
  * A—“for every path”
  * E—“there exists a path”
* State quantifier:
  * Fp—p holds sometime in the future
  * Gp—p holds globally in the future
  * Xp—p holds next time
  * pUq—p holds until q holds

## Examples:

EF(started & !ready): it is possible to get to a state where started holds but ready does not hold.

---

AG(req -> AF ack): if a request occurs, then it will be eventually acknowledged.

---

AG(AF device enabled): enabled holds infinitely often on every computation path.

---

AG(EF restart): from any state it is possible to get to the restart state.
