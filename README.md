# dot_tab_indicator

Dot TabBar indicator

# Getting started

```dart
TabBar(
  isScrollable: true,
  controller: _tabController,
  labelColor: Colors.black,
  tabs: <Widget>[
    Tab(text: 'DOTTED'),
    Tab(text: 'Tab'),
    Tab(text: 'INDICATOR'),
  ],
  indicator: DotIndicator(
    indicatorColor: Colors.black,
    radius: kDefaultDotIndicatorRadius,
  ),
  indicatorWeight: 2 * kDefaultDotIndicatorRadius,
),
```
