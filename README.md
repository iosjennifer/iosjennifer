## Online test questions
### 1. NSDate's timeIntervalSinceNow can NOT be used for:
   a. profiling code<br>
   b. measuring total application startup time<br>
   c. measuring the time a method took to run in two different threads<br>
   d. measuring time since the user performed an action<br>
   e. measuring the time it takes a section of code to run<br>
### 2. `-(void)processData:(id)someData{}`<br>Based on the sample code above, which code do you use to test if someData is an NSString?
   a. ```if([someData isTypeOf:[NSString getClass]])```<br>
   b. ```if([someData isClass:@"NSString"])```<br>
   c. ```if([someData isClass:NSString])```<br>
   d. ```if([someData isKindOfClass:[NSString class]])```<br>
   e. ```if([someData isOfKind:[NSString class]])```<br>
### 3. In regard to autorelease pools, which additional step do you take when you detach a thread?
   a. Create your own autorelease pool for it<br>
   b. Do not use autorelease objects of any kind in the thread's code<br>
   c. Do not drain or release the autorelease pool created in the main thread<br>
   d. Get a reference to the autorelease pool created in the main thread<br>
   e. Ensure the threads share a memory page so the parent thread's autorelease pool can manage the thread's objects<br>
### 4. How do you write code to get an instance of a class UISuperBlog which may now be present at runtime?
   a. `Class superBlog = [[UISuperBlog alloc] init];`<br>
   b. `Class superBlog = [[NSClassFromString(@"UISuperBlog") alloc] init];`<br>
   c. `Class superBlog = [[NSClassFromString("UISuperBlog") malloc] init];`<br>
   d. `Class superBlog = [[NSClassIfExists(@"UISuperBlog") alloc] init];`<br>
   e. `Class superBlog = [[NSClassAtRuntime(@"UISuperBlog") alloc] init];`<br>
### 5. When you create a UINavigationController, which components are automatically created along with it?
   a. UIWindow and UINavigationBar<br>
   b. UISubView and UIContainer<br>
   c. UIView and UINavigationBar<br>
   d. UIView and UINatigationItem<br>
   e. UIScrollView and UIWindow<br>
### 6.Based on the sample code below, which code do you insert in place of "Insert code here" on line 2 to gain access to the additional information passed along with the notification?
```
- (void)notificationHandler:(NSNotification *)notification{
        //Insert code here   
        NSLog(@"First Name:%@",[additionalData objectForKey:@"firstName"]);
   }
```
   a. `NSArray* additionalData = [notification userInfo];`<br>
   b. `NSDictionary* additionalData = [notification retrieve:@"userInfo"];`<br>
   c. `NSArray* additionalData = [notification getData];`<br>
   d. `NSNotification* additionalData = [notification extendedData];`<br>
   e. `NSDictionary* additionalData = [notification userInfo];`<br>
### 7. You are writing a relatively simple application that runs on a simple thread. You have a number of classes, each with a number of synthesized properties. You notice that your application appears to be slower than expected when doing a large number of property get/set operations. Based on this scenario, which change do you make to maximize the application's performance?
   a. Use an autorelease pool when accessing the properties.<br>
   b. Ensure all properties specify the atomic attribute.<br>
   c. Change the properties to nonatomic.<br>
   d. Add retain to all property directives.<br>
   e. Write custom accessors and mutators.<br>    
### 8. Which is the default setter semantic attribute?
   a. strong<br>
   b. retain<br>
   c. copy<br>
   d. weak<br>
   e. assign<br>    
### 9. How do you change the interval of an existing NSTimer?
   a. Change the interval property of it.<br>
   b. Call the cancelTimer method and then create a new one.<br>
   c. Set the reference to it to nil.<br>
   d. Call the changeInterval method on it.<br>
   e. Invalidate it and then create a new one.<br>   
### 10. The addSubview method of UIView retains:
   a. neither the view nor the controller.<br>
   b. the view and controller, if derived form Retainable.<br>
   c. both the view and the controller.<br>
   d. the view but not the controller.<br>
   e. the controller but not the view.<br>
