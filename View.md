
#### Use to preview dark mode

```swift
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
            .preferredColorScheme(.light)
        ContentView()
            .preferredColorScheme(.dark)
    }
}

```

#### Concepts for SwiftUI
1. Only three ways to layout views (VStack, HStack, ZStack)
2. Everyting is a view
- adding property to an existing view, is replacing it, not changing it.
- parent view, and child view, properties add to the parent view, change all child views. 
- changes in child views, overrides changes in parent views.
3. Pulling View, Pushing out View, (Pushing Views will eat out all the spaces they can eat)
4. Change Views with DATA
- If you want to change the view, you have to change the data, you can't change views directly. Like "@State".
