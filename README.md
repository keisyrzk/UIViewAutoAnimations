# UIViewAutoAnimations

##FUNCTIONALITY
This UIView extension allows:
- to add a custom blurred effect to any UIView class.
- to make any UIView automatically show up/hide with animation from/over the closest edge of its superview with a given direction (vertical or horizontal)

##EXPLANATION
###BLURRED EFFECT
Just call an extension with:
```
myView.blurred(style: .dark, alpha: 0.7, cornerRadius: 10, corners: [.bottomRight, .topRight])
```
Afer that the "myView" will have a blurred dark-styled background with rounded bottom-right and top-right corners with a radius of 10.

###AUTO SHOW UP/HIDE
Let us say that you set a CollectionView on the top of the current view. You would like to shop it up and hide automatically if a single command. All you need to do to say that you want your collection view animate in direction you want.
```
myCollectionView.showOrHide(direction: .Vertical)
```
This will cause your collection view hide (if it is currently visible) or show up (if it is already hidden).
