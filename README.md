# UIViewAutoAnimations

#FUNCTIONALITY
This UIView extension allows:
- to add a custom blurred effect to any UIView class.
- to make any UIView automatically show up/hide with animation from/over the closest edge of its superview with a given direction (vertical or horizontal)

#EXPLANATION
Let us say that you set a CollectionView on the top of the current view. You would like to shop it up and hide automatically if a single command. All you need to do to say that you want your collection view animate in direction you want.
myCollectionView.showOrHide(direction: .Vertical)
