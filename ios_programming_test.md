# UPWORK IOS PROGRAMMING TEST 2016

1. Which of the following is the correct way to set the font size of UIButton title label?  
  Answers:
  * someButton.font = [UIFont systemFontOfSize: 15];
  * someButton.titleLabel.font = [UIFont systemFontOfSize: 15];
  * [someButton setFont: [UIFont systemFontOfSize: 15]];
  * All of the above

2. Which of the following frameworks is needed to apply a border to an object?  
  Answers:
  * UIKit
  * CoreGraphics
  * QuartzCore
  * Foundation

3. What is the maximum size of an iOS application?  
  Answers:
  * 20 MB
  * 50 MB
  * 1 GB
  * 2 GB

4. Which of the following will set an image on UIButton?  
  Answers:
  * button.image = [UIImage imageNamed:@"btn_img.png"];
  * button.imageView.image = [UIImage imageNamed:@"btn_img.png"];
  * [button setImage:[UIImage imageNamed:@"btn_img.png"] forState:UIControlStateNormal];
  * [button setImageView:[UIImage imageNamed:@"btn_img.png"] forState:UIControlStateNormal];

5. Which of the following is the best way to add a UIToolbar above keyboard?  
  Answers:
  * -(void)keyboardWillShow:(NSNotification *)notification { [self.view addSubview:toolbar]; }
  * -(void)textFieldDidBeginEditing:(UITextField *)textField { [self.view addSubview:toolbar]; }
  * Always keep UIToolBar visible on screen.
  * -(void)keyboardWillHide:(NSNotification *)notification { [self.view addSubview:toolbar]; }

6. Select all incorrect bundle ID(s):  
    Answers:
    * com.company.appName
    * com.appName
    * appName
    * com.company-name.app-name

7. Which one is true regarding integrating and using custom fonts in an iOS application?  
  Answers:
  * Apple rejects the applications that use custom fonts.
  * Adding fonts to your app plist allows usage directly in the app.
  * There is no direct way to add fonts; third party APIs are the only way.
  * You can add fonts, but only if they are provided by Apple.

8. Which of the following is not a valid UIGestureRecognizer?  
  Answers:
  * UITapGestureRecognizer
  * UIZoomGestureRecognizer
  * UIRotationGestureRecognizer
  * UIPanGestureRecognizer

9. What is the correct method to define a delegate object in an ARC Environment?  
  Answers:
  * @property (nonatomic, weak) id &#60;MyClassDelegate> delegate;
  * @property(nonatomic,retain) id &#60;MyClassDelegate> delegate;
  * @property(nonatomic,weak) &#60;MyClassDelegate> delegate;
  * @property(nonatomic, weak) NSObject *delegate;

10. Is it possible to set multiple architecture from Build Settings tab in Xcode for a project?  
  Answers:
  * Yes
  * No
  * only in Xcode 4.5 or later
  * only in Xcode 4.5 or previous

11. Is it possible to deploy beta build on any device?  
  Answers:
  * Yes beta build can be deployed on any iOS device.
  * Beta build can be deployed only on devices that are included in Mobile Provision certificate while compiling build.
  * Beta Build can be deployed only on Simulators.
  * All of above

12. Which of the following is not an Open Source Framework/Library?  
  Answers:
  * MBProgressHUD
  * ASIHTTPRequest
  * RestKit
  * StoreKit

13. Which of the following framework is needed to round corners of UILabel?  
  Answers:
  * UIKit
  * CoreGraphics
  * QuartzCore
  * CoreAnimation

14. Which of the following is not a valid icon size for any iOS device (iPhone, iPod, iPad)?  
  Answers:
  * 114 x 114
  * 144 x 144
  * 72 x 72
  * 64 x 64

15. Which of the following correctly describes when the — (void)viewDidUnload method is called?  
  Answers:
  * When the application launches.
  * When any view appears.
  * When a view is released.
  * During low memory conditions when the view controller needs to release its view.

16. What is the use of performSelector in iOS?  
  Answers:
  * To add a class delegate
  * To define a class
  * To call a method of a class
  * To add a selector method

17. How can an alert message/pop-up dialog box be shown in IOS?  
  Answers:
  * UIAlertView *alert = [[UIAlertView alloc] initWithTitle:@“test message” message:@“test message for application.” delegate:nil cancelButtonTitle:@“OK” otherButtonTitles:nil]; [alert show];
  * UIAlertView *alert = [[UIAlertView mess] initWithTitle:@“test message” message:@“test message for application.” delegate:nil cancelButtonTitle:@“OK” otherButtonTitles:nil]; [alert show]; [alert release]; 
  * UIAlertView *alert = [[UIAlertView mess] initWithTitle:@“test message” message:@“test message for application.” delegate:nil cancelButtonTitle:@“OK” otherButtonTitles:nil]; [alert display]; 
  * UIAlertView *alert = [[UIAlertView mess] initWithTitle:@“test message” message:@“test message for application.” delegate:nil cancelButtonTitle:@“OK” otherButtonTitles:nil]; [alert display]; [alert release];

18. Which of the following is not a valid MKAnnotationView property?  
  Answers:
  * canShowCallout
  * draggable
  * dragState
  * None of these.

19. Which of the following is not used to find an object contained in NSMutableArray?  
  Answers:
  * “[myArray filteredArrayUsingPredicate:[NSPredicate predicateWithFormat:“”self == %@””,@””new””]];”
  * [myArray indexOfObject:@”New”];
  * [myArray containObject:@”New”]; ( [myArray containsObject:@”New”]; )
  * [myArray objectPresent];

20. Which framework can be used to call SOAP web services in iOS applications?  
  Answers:
  * gSOAP
  * ASIHTTP framework
  * wsdl2objc framework
  * None of these

21. Which of the following changes the color of the pagination dots of UIPageControl?  
  Answers:
  * setPageIndicatorTintColor
  * setCurrentPageIndicatorTintColor
  * setColor
  * A custom page control view implementation

22. Where does Xcode place its build products and other intermediaries/temporary files?  
  Answers:
  * In the Derived Data folder
  * In the Archives folder
  * In the User Data folder
  * In the application Document folder

23. Which of the following will print the value of a Boolean flag in NSLog?  
  Answers:
  * NSLog(@“Bool value: %@”,value)
  * NSLog(@“Bool value: %d”,value)
  * NSLog(@“Bool value: %d.d”,value)
  * None of the above

24. Which of the following is not a valid MPVolumeView method?  
  Answers:
  * — (CGRect)volumeThumbRectForBounds:(CGRect)bounds volumeSliderRect:(CGRect)rect value:(float)value
  * — (UIImage *)maximumVolumeSliderImageForState:(UIControlState)state
  * — (CGRect)routeButtonRectForBounds:(CGRect)bounds
  * — (void)setVolumeThumbImage:(UIImage *)image

25. What is true about Grand Central Dispatch(GCD) and NSOperation?  
  Answers:
  * GCD is a low level C- based API and NSOperation is Objective -C class
  * NSOperation is low-level C-based API and CGD is Objective — C classes
  * Both are Objective — C classes
  * None of the above

26. Which of the following will make an iPhone app return its own version number?  
  Answers:
  * [NSString stringWithFormat: @ “Version %@ (%@)”,[[[NSBundle mainBundle] infoDictionary] objectForKey:@“CFBundleVersion”], ]
  * [NSString stringWithFormat: @ “Version %@ (%@)”,[[[NSBundle mainBundle] infoDictionary] objectForKey:@“CFBundleVersion”], kRevisionNumber]
  * [NSString stringWithFormat: @ “Version ”,[[[NSBundle mainBundle] infoDictionary] objectForKey:@“CFBundleVersion”], kRevisionNumber]
  * [NSString stringWithFormat: @ “Version %@ (%@)”,[[[NSBundle mainBundle] Dictionary] objectForKey:@“CFBundleVersion”], kRevisionNumber]

27. Which of the following will return the device’s current location?  
  Answers:
  * CLLocationManager locationManager = [[CLLocationManager alloc] init]; [locationManager startUpdatingLocation];
  * CLLocationManager locationManager = [[CLLocationManager alloc] init]; [locationManager updateLocation];
  * CLLocationManager locationManager = [[CLLocationManager alloc] init]; [locationManager getLocation];
  * CLLocationManager locationManager = [[CLLocationManager alloc] init]; [locationManager findLocation];

28. Which of the following is best JSON library to be used in iOS applications?  
  Answers:
  * SBJSON
  * JSON kit
  * Touch JSON
  * None of these

29. Which of the following will set the font of UISegmentedControl?  
  Answers:
  * UIFont *font = [UIFont boldSystemFontOfSize:12.0f]; NSDictionary *attributes = [NSDictionary dictionaryWithObject:font forKey:UITextAttributeFont]; [segmentedControl setTitleTextAttributes:attributes forState:UIControlStateNormal];
  * [[UISegmentedControl appearance] setTitleTextAttributes:[NSDictionary dictionaryWithObjectsAndKeys:[UIFont fontWithName:@"STHeitiSC-Medium" size:13.0], UITextAttributeFont, nil] forState:UIControlStateNormal];
  * segmentedControl.transform = CGAffineTransformMakeScale(.6f, .6f);
  * None of these.

30. When does this behavior usually happen?  
  >"Xcode Message: finished running &#60;my app>" on targeted device shows, but nothing happens
  
  Answers:
  * If the app was ran on earlier devices (3G or 3GS) and arm6 was not added in Require Device Capabilities.
  * If app was built and ran on version 3.2 or earlier of Xcode and arm7 was not added in Require Device Capabilities.
  * If Bundle Identifier used in the project is being used by another project
  * When some another application is already running on device
  * When the device is locked with a passcode

31. Which of the following font packages are supported by Cocoa-Touch?  
  Answers:
  * .ttf (True Type Font)
  * .ttc (True Type font Collection)
  * .otf (Open Type Font)
  * .dFont (MAC OS X Data Fork Font)

32. Which of the following is the correct way to set UIButton’s Highlight Tint color programmatically?  
  Answers:
  * [button setColor:[UIColor grayColor]];
  * [button setTintColor:[UIColor grayColor]];
  * [button setColor:[UIColor grayColor]];
  * [button TintColor:[UIColor grayColor]];

33. Which of the following will change the placeholder text color in UITextField?  
  Answers:
  * textField.placeHolder.textColor = [UIColor redColor];
  * textField.placeHolder.textLabel.textColor = [UIColor redColor];
  * textField.placeHolder.color = [UIColor redColor];
  * None of the above.

34. Select which of the following is not UITableViewCellSelectionStyle values?  
  Answers:
  * UITableViewCellSelectionStyleNone
  * UITableViewCellSelectionStyleBlue
  * UITableViewCellSelectionStyleLightGray
  * UITableViewCellSelectionStyletGray

35. Which of the following is the correct way to get the value of the first object of a NsMutableArray stored in another NsMutableArray?  
  Answers:
  * [[myArray objectAtIndex:0] objectAtIndex:0];
  * [myArray objectAtIndex:0]
  * [[[myArray objectAtIndex:0] objectAtIndex:0]objectAtIndex:0];
  * [myArray firstObject]

36. How can the application name of an iOS project be changed?  
  Answers:
  * Change Bundle Display Name from info.plist
  * Rename Project
  * Change bundle identifier
  * Create a new project with New name

37. Which method is used to dismiss keyboard for UITextField?  
  Answers:
  * [textField becomesFirstResponder];
  * [textField dismissKeyboard];
  * [textField resignFirstResponder];
  * [textField shouldReturn];

38. Which of the following UILabel properties help adjust text within a UILabel?  
  Answers:
  * lineBreakMode
  * adjustsFontSizeToFitWidth
  * numberOfLines
  * drawTextInRect:

39. Consider the following code:  
  >(BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {  
  // Set Background Color/Pattern  
  self.window.backgroundColor = [UIColor blackColor];  
  self.tabBarController.tabBar.backgroundColor = [UIColor clearColor];  
  //self.window.backgroundColor = [UIColor colorWithPatternImage:[UIImage imageNamed:@"testbg.png"]];  
  // Set StatusBar Color  
  [[UIApplication sharedApplication] setStatusBarStyle:UIStatusBarStyleBlackTranslucent];  
  // Add the tab bar controller’s current view as a subview of the window  
  self.window.rootViewController = self.tabBarController;  
  [self.window makeKeyAndVisible];  
  return YES;  
  }  
  
  How can the error be corrected that gets thrown in the console, "Applications are expected to have a root view controller at the end of application launch"?  
  
  Answers:
  * self.window = [[[UIWindow alloc] initWithFrame:[[UIScreen mainScreen] bounds]] autorelease];
  * MenuViewController *menuViewController = [[MenuViewController alloc]init]; self.window.rootViewController = menuViewController;
  * Both
  * None of above

40. Which of the following allows it to determine if an application is running on iPhone, or if it’s running on an iPod Touch?  
  Answers:
  * NSString *deviceType = [UIDevice currentDevice].model; if([deviceType isEqualToString:@"iPhone"])
  * NSString *deviceType = [UIDevice currentDevice].Size; if([deviceType isEqualToString:@"iPhone"])
  * NSString *deviceType = [UIDevice currentDevice].device; if([deviceType isEqualToString:@"Device"])
  * NSString *deviceType = [UIDevice currentDevice].iPhone; if([deviceType isEqualToString:@"iPhone"])

41. What is true about ARC and manual memory management?  
  Answers:
  * Always nil out properties in dealloc under ARC and manual memory management.
  * Do not have to nil out properties in dealloc under ARC and manual memory management.
  * nil out properties in dealloc under ARC but not in manual memory management.
  * nil out properties in dealloc under manual memory management but not in ARC.

42. What does the "strong" property attribute do?  
  Answers:
  * It does not extend the lifetime of the object it points to, and automatically becomes nil.
  * It specifies a reference that does not keep the referenced object alive and is not set to nil.
  * It makes the object alive, as long as there is a strong pointer to it.
  * It specifies a reference that does not keep the referenced object alive and is not set to nil.

43. Which of the following is the best practice to find an active internet connection?  
  Answers:
  * — (BOOL) connectedToInternet { Reachability *reachability = [Reachability reachabilityForInternetConnection]; NetworkStatus networkStatus = [reachability currentReachabilityStatus]; return !(networkStatus == NotReachable); }
  * — (BOOL) connectedToInternet { NSString *URLString = [NSString stringWithContentsOfURL:[NSURL URLWithString:@"http://www.google.com"]]; return ( URLString != NULL ) ? YES : NO; }
  * — (BOOL) connectedToInternet { NSURL *URLString = [NSURL URLWithString:@"http://www.google.com"]; NSData *data = [NSData dataWithContentsOfURL:URLString]; if (data) return YES; else return NO; }
  * — (BOOL) connectedToInternet { NSMutableURLRequest *request = [NSMutableURLRequest requestWithURL: [NSURL URLWithString:@"http://www.google.com/"]]; [request setHTTPMethod:@"HEAD"]; NSHTTPURLResponse *response; [NSURLConnection sendSynchronousRequest:request returningResponse:&response error: NULL]; return ([response statusCode] == 200) ? YES : NO; }

44. What gets returned if XIB is not properly connected to a parent controller?  
  Answers:
  * EXEC_BAD_ACCESS
  * SIGABRT
  * SIGKILL
  * None of these.

  45. How can it be detected if the app is running on an iPhone 5?  
  Answers:
  * if(UI_USER_INTERFACE_IDIOM() == UIUserInterfaceIdiomPhone5)
  * if([[UIScreen mainScreen] bounds].size.height == 568)
  * if([[UIScreen mainScreen] bounds].size.height == 1136)
  * if([[UIDevice currentDevice].model isEqualToString:@"iPhone5″])

46. Which of the following is not a valid Touch method with respect to Cocoa Touch programming?  
  Answers:
  * — (void)touchesBegan:(NSSet *)touches withEvent:(UIEvent *)event
  * — (void)touchesMoved:(NSSet *)touches withEvent:(UIEvent *)event
  * — (void)touchesEnded:(NSSet *)touches withEvent:(UIEvent *)event
  * None of above

47. Which of the following is the correct way to print out stack/trace to the console/log in Cocoa application?  
  Answers:
  * NSLog(@”%@”,[NSThread callStackSymbols]);
  * NSLog(@”%@”,[NSThread callStackReturnAddresses ])
  * NSLog(@”%@”,[NSThread currentThread]);
  * None of the above.

48. Which of the following is not a valid UIGestureRecognizer?  
  Answers:
  * UITapGestureRecognizer
  * UIZoomGestureRecognizer
  * UIRotationGestureRecognizer
  * UIPanGestureRecognizer

49. Which of the following correctly sets an image on UIButton?  
  Answers:
  * button.image = [UIImage imageNamed:@"button_img.png"];
  * button.imageView.image = [UIImage imageNamed:@"button_img.png"];
  * [button setImage:[UIImage imageNamed:@"button_img.png"] forState:UIControlStateNormal];
  * [button setImageView:[UIImage imageNamed:@"button_img.png"] forState:UIControlStateNormal];

50. Which of the following is the best practice to find active internet connection?  
  Answers:
  * — (BOOL) connectedToInternet { Reachability *reachability = [Reachability reachabilityForInternetConnection]; NetworkStatus networkStatus = [reachability currentReachabilityStatus]; return !(networkStatus == NotReachable); }
  * — (BOOL) connectedToInternet { NSString *URLString = [NSString stringWithContentsOfURL:[NSURL URLWithString:@"http://www.google.com"]]; return ( URLString != NULL ) ? YES : NO; }
  * — (BOOL) connectedToInternet { NSURL *URLString = [NSURL URLWithString:@"http://www.google.com"]; NSData *data = [NSData dataWithContentsOfURL:URLString]; if (data) return YES; else return NO; }
  * — (BOOL) connectedToInternet { NSMutableURLRequest *request = [NSMutableURLRequest requestWithURL: [NSURL URLWithString:@"http://www.google.com/"]]; [request setHTTPMethod:@"HEAD"]; NSHTTPURLResponse *response; [NSURLConnection sendSynchronousRequest:request returningResponse:&response error: NULL]; return ([response statusCode] == 200) ? YES : NO; }

51. What will be output of following code?  
  >NSLog(@"%.2f",[[UIDevice currentDevice].systemVersion floatValue]);  
  
  Answers:
  * 6.1.0
  * 6.1.2
  * 6.10
  * 6.12

52. What is the difference between new and [[alloc]init] in iOS?  
  Answers:
  * [[alloc]init] is used to create an object but new is not used to create an object.
  * Neither [[alloc]init] nor new is used for creating an object.
  * No difference. Both [[alloc]init] and new are used to create an object.
  * [[alloc]init] is not used to create object but new is used to an create object.

53. What could be the probable result if selector is unknown or undefined?  
  Answers:
  * Causes memory leak
  * Causes application to terminate with error
  * Nothing will happen
  * None of above

54. Which of the following properties would be used to draw a shadow under UIView?  
  Answers:
  * CGContextRestoreShadowState
  * CGContextRestoreGState
  * CGContextSetShadow();
  * CGContextshadowState

55. Which of the following is the correct way to check whether the view controller view is loaded or visible?  
  Answers:
  * if (viewController.isViewLoaded || tabbarController.view.window) { // viewController is visible }
  * if([[[self tabBarController] selectedViewController] isEqual:self]){ //we’re in the active controller }else{ //we are not }
  * if (viewController.isLoaded && viewController.view.) { // viewController is visible }
  * if (viewController.isViewLoaded && viewController.view.window) { // viewController is visible }

56. Which of the following is the correct way to transfer data from one view controller to another?  
  Answers:
  * EditingViewController *controller = [[EditingViewController alloc] initWithNibName:@"EditingView" bundle:nil]; controller.editedObject = book; … [self.navigationController pushViewController:controller animated:YES]; [controller release]; In the Editing View (EditingViewController): — (IBAction)save { … [editedObject setValue:datePicker.date forKey:editedFieldKey]; [editedObject setValue:textField.text forKey:editedFieldKey]; } [self.navigationController popViewControllerAnimated:YES]; }
  * NSString *commString; in appDelegate. And then when you submit the uitextfield value just assign that text field value to the appDelegate.commString use this in the next view. ProjectNameAppDelegate *appDelegate = [[UIApplication sharedApplicatoin] delegate]; appDelegate.commString = textField.text;
  * Both 1 and 2 methods are correct.
  * None of above are correct.

57. Which of the following is the correct way to set the Navigation Bar Color of the Tab Bar Configure Menu?  
  Answers:
  * "UINavigationController *navigationController; … navigationController.navigationBar.tintColor = [UIColor blackColor];"
  * "UINavigationController *navigationController; … navigationController.tintColor = [UIColor blackColor];"
  * "UINavigationController *navigationController; … navigationController.color = [UIColor blackColor];"
  * "UINavigationController *navigationController; … navigationController.navigationBar.Color = [UIColor blackColor];"

58. What does EXC_BAD_ACCESS signal received mean in Xcode?  
  Answers:
  * Due to warning in code
  * "Owning" the memory but forgetting to release
  * Testing on a device without registering UDID
  * Using incorrect delegate methods

59. How can an SMS be sent programmatically from the iPhone (iOS 4.0 or later)?  
  Answers:
  * Using MFMessageComposeViewController
  * [[UIApplication sharedApplication] openURL: @"sms:PHONE-NUMBER"];
  * Both A &B are correct answers
  * The official SDK/Cocoa Touch doesn’t allow sending SMSs programmatically

60. What is the difference between assign and retain in Objective-C?  
  Answers:
  * assign — Specifies that a copy of the object should be used for assignment. The previous value is sent a release message. retain — Specifies that the setter uses simple assignment. The previous value is sent a release message.
  * assign — Specifies that the setter uses simple assignment. This is the default. retain — Specifies that retain should be invoked on the object upon assignment. The previous value is sent a release message.
  * assign — Increases the count of an object by 1. Takes ownership of an object. retain — Decreases the retain count of an object by 1. Relinquishes ownership of an object.
  * assign — Makes a assign of an object, and returns it with retain count of 1. If you copy an object, you own the copy. retain — Specifies that a retain of the object should be used for assignment. The previous value is sent a release message.

61. Which property would be used to get the UDID of UIDevice on iOS?  
  Answers:
  * [UIDevice UDIDString]
  * [UIDevice uniqueIdentifier]
  * -[UIDevice identifierForVendor]
  * None of these

62. What property in info.plist handles the association of file types in an iPhone application?  
  Answers:
  * LSItemContentTypes
  * LSHandlerRank
  * CFBundleTypeName
  * CFBundleTypeRole

63. Which method of Objective-C handles detecting the shake gesture on an iOS device?  
Answers:  
  * + (UIAccelerometer *)sharedAccelerometer
  * — (void) accelerometer:(UIAccelerometer *)accelerometer didAccelerate:(UIAcceleration *)acceleration
  * — (void) accelerometer:(UIAccelerometer *)accelerometer willAccelerate:(UIAcceleration *)acceleration
  * — (void) accelerometer:(UIAccelerometer *)accelerometer beginAccelerate:(UIAcceleration *)acceleration

64. Which one is the best resolution for the following error?  
  "A valid signing identity matching this profile could not be found in your keychain"  
  Answers:
  * Installing the certificate file in your keychain
  * Renewing your provisioning profile
  * Installing the private key in your keychain
  * Renewing your Apple developer account.

65. What is the best way to show multiple lines text in the UILabel?  
  Answers:
  * CGRect currentFrame = myLabel.frame; CGSize max = CGSizeMake(myLabel.frame.size.width, 500); label.font = [UIFont systemFontOfSize:13.0]; CGSize expected = [myString sizeWithFont:myLabel.font]; myLabel.numberOfLines = 0;
  * CGRect currentFrame = myLabel.frame; CGSize max = CGSizeMake(myLabel.frame.size.width, -1); CGSize expected = [myString sizeWithFont:myLabel.font]; myLabel.numberOfLines = -1;
  * myLabel.numberOfLines = 0; CGRect currentFrame = myLabel.frame; CGSize max = CGSizeMake(myLabel.frame.size.width, 500); CGSize expected = [myString sizeWithFont:myLabel.font constrainedToSize:max lineBreakMode:myLabel.lineBreakMode]; currentFrame.size.height = expected.height; myLabel.frame = currentFrame;
  * You have to use UITextView for this purpose, otherwise Apple will rejects your app submission.

66. What does a "__block" type specifier mean?  
  Answers:
  * Modifications made with the variable marked with __block inside the block are not visible outside of it.
  * Modifications done with the variable marked with __block inside the block are also visible outside of it.
  * It makes the variable non-mutable within the block.
  * None of the above

67. Which of the following code samples will declare a variable inside a block in Objective-C?  
  Answers:
  * Person *aPerson = nil; [participants enumerateObjectsUsingBlock:^(id obj, NSUInteger idx, BOOL *stop) { Person *participant = (Person*)obj; if ([participant.gender isEqualToString:@"M"]) { aPerson = participant; *stop = YES; } }]; return aPerson;
  * __block Person *aPerson = nil; [participants enumerateObjectsUsingBlock:^(id obj, NSUInteger idx, BOOL *stop) { Person *participant = (Person*)obj; if ([participant.gender isEqualToString:@"M"]) { aPerson = participant; *stop = YES; } }]; return aPerson;
  * [participants enumerateObjectsUsingBlock:^(id obj, NSUInteger idx, BOOL *stop) { Person *participant = (Person*)obj; Person *aPerson = nil; if ([participant.gender isEqualToString:@"M"]) { aPerson = participant; *stop = YES; } }]; return aPerson;
  * All of the above.

