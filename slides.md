footer: @iwantmyrealname

#[fit] Views & Animations:
#[fit] __Learning__ by
#[fit] _Stealing_


[github.com/sammyd/MobileUnplugged2018_UI](https://github.com/sammyd/MobileUnplugged2018_UI)

---

# [fit] _why_
# [fit] __steal?__

---

#[fit] _where_ to
#[fit] __start?__

---

![autoplay loop fit](img/express_vpn.MOV)

---

![fit](img/express01.png)

---

![fit](img/express02.png)

---

![fit](img/express03.png)

---

#[fit] Views -vs- layers
#[fit] `CAShapeLayer`
#[fit] `UIBezierPath`
#[fit] Layer shadows

---

#[fit] #code

---

![fit](img/express04.png)

---

#[fit] `CAShapeLayer`
#[fit] `CAGradientLayer`
#[fit] Layer masks

---

![fit original](img/PaintCodeIcon.png)

PaintCode

---

![fit original](img/KiteIcon.png)

KiteApp

---

#[fit] #code

---

![fit](img/express05.png)

---

![fit](img/express06.png)

---

![fit](img/express07.png)

---

![fit](img/express08.png)

---

#[fit] `CAGradientLayer`
#[fit] Layer Masks
#[fit] `CAAnimation`

---

#[fit] #code

---

![fit](img/express09.png)

---

![fit](img/express10.png)

---

![fit](img/express11.png)

---

#[fit] `CAAnimation`
#[fit] Layer masks
#[fit] `CAShapeLayer`

---

#[fit] __so__
#[fit] what?

---

#[fit] learning

---

#[fit] practice

---

#[fit] mistakes

---

![autoplay loop fit](img/maps.MOV)

---

#[fit] Custom modal
#[fit] Presentation controller
#[fit] Transitioning delegate
#[fit] Property animator

---

#[fit] _interactive_
#[fit] map?

---

```swift
override func hitTest(_ point: CGPoint,
                   with event: UIEvent?) -> UIView? {
  let hit = super.hitTest(point, with: event)
  if hit != self {
    return hit
  }
  for passthroughView in passthroughViews {
    let hit = passthroughView.hitTest(
      convert(point, to: passthroughView),
      with: event)
    if hit != .none {
      return hit
    }
  }
  return .none
}
```

---

#[fit] __incorrect__
#[fit] model

---

#[fit] _maybe_
#[fit] __contained__
#[fit] view controllers

---

#[fit] _doesn't_
#[fit] __matter__

---

#[fit] __learning__

---

#[fit] __practice__

---

#[fit] __mistakes__

---

![](img/iat.png)

---

#[fit] @iwantmyrealname

#[fit]~

#[fit] [github.com/sammyd](https://github.com/sammyd/MobileUnplugged2018_UI)
#[fit] [/MobileUnplugged2018_UI](https://github.com/sammyd/MobileUnplugged2018_UI)
