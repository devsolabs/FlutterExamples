# Flutter Snippets
A curated collection of most frequently used flutter snippets


- [Material Design](#view)
- [Context](#context)
- [Fragment](#fragment)
- [Activity](#activity)
- [ViewGroup](#viewgroup)
- [TextView](#textview)
- [String](#string)
- [Other](#other)

## Material Design



```dart
/**
 * Extension method to provide simpler access to {@link View#getResources()#getString(int)}.
 */
fun View.getString(stringResId: Int): String = resources.getString(stringResId)
```


