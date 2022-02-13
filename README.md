# ObjectTableViewController

A simple property list viewer in Objective-C.

## Usage

```objective-c
ObjectTableViewController *ctrl = [[ObjectTableViewController alloc] initWithPath:[[NSBundle mainBundle] pathForResource:@"Info" ofType:@"plist"]];
ctrl.pullToReload = YES;
ctrl.pressToCopy = YES;
ctrl.showTypeHint = YES;
ctrl.allowSearch = YES;
ctrl.initialRootExpanded = YES;
UINavigationController *navCtrl = [[UINavigationController alloc] initWithRootViewController:ctrl];
[self presentViewController:navCtrl animated:YES completion:nil];
```
