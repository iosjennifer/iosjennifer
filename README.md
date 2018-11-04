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
