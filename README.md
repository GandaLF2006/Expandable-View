## Expandable-View
Simple ExpandableView for iOS app.

### Installation 
Add this file to your project.

### Usage
1. You need to create a View object in your Storyboard and set it's class to `ExpandableView`.
2. Then create 2 UIView objects inside of it, create a height constraints for each and connect them as `firstView` and `secondView`.
3. This class creates constraints for `firstView` and `secondView`. You should not add them.
4. Done. You can tap your expandableView or use `expand()` and `collapse()` methods to change its state.

#### If you don't want to have any warning inside of your Interface Builder, you can add all constraints you need and set them to remove at build time.

#### I will add support for easier initialization in the future.
