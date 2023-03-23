

![Animation](https://raw.githubusercontent.com/leesnhyun/flashy_tab_bar/master/docs/animation.gif)

## Preview

| Android  | iOS  |
| :------------------- | -------------------: |
| <img src="https://raw.githubusercontent.com/leesnhyun/flashy_tab_bar/master/docs/emulator-android.gif" height="714">  | <img src="https://raw.githubusercontent.com/leesnhyun/flashy_tab_bar/master/docs/emulator-ios.gif" height="714"> |

## Getting Started

Add the dependency at pubspec.yaml:

```yaml
dependencies:
  ...
  flashy_tab_bar2: ^0.0.5
```

## Basic Usage

```dart
bottomNavigationBar: FlashyTabBar(
     selectedIndex: _selectedIndex,
     showElevation: true,
     onItemSelected: (index) => setState(() {
       _selectedIndex = index;
     }),
     items: [
        FlashyTabBarItem(
          icon: Icon(Icons.event),
          title: Text('Events'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.search),
          title: Text('Search'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.highlight),
          title: Text('Highlights'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.settings),
          title: Text('Settings'),
        ),
        FlashyTabBarItem(
          icon: Icon(Icons.settings),
          title: Text('한국어'),
        ),
      ],
),
```
