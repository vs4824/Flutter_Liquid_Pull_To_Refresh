# Flutter Liquid Pull To Refresh

A beautiful and custom refresh indicator for flutter highly inspired from Ramotion Pull Down to Refresh. Try out our live example app.

## Installing

1. Depend on it

Add this to your package's pubspec.yaml file:

   ```
   dependencies:
  liquid_pull_to_refresh: ^3.0.1
   ```

2. Install it

You can install packages from the command line:

with pub:

   ```
   $ pub get
   ```

with Flutter:

   ```
   $ flutter packages get
   ```

3. Import it

Now in your Dart code, you can use:

   ```
   import 'package:liquid_pull_to_refresh/liquid_pull_to_refresh.dart';
   ```

### Usage

For adding this custom refresh indicator in your flutter app, you have to simply wrap ListView or GridView inside LiquidPullToRefresh. Also you have provide the value of onRefresh parameter which is a refresh callback.

Note - LiquidPullToRefresh can only be used with a vertical scroll view.

For example:

   ```
   LiquidPullToRefresh(
        key: _refreshIndicatorKey,	// key if you want to add
        onRefresh: _handleRefresh,	// refresh callback
        child: ListView(),		// scroll view
      );
   ```


