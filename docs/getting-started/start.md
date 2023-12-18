Where should I start?
-----

It's really up to you where you want to start, but if it's your first time in the VM space I really reccomend trying to install windows 10 on a virtual machine, i have a [**GUIDE**] for it right on this document, if you're experienced then you can attempt to experiment with beta operating systems. (currently I am experimenting with beta operating systems on my [**TWITCH**] (https://www.twitch.tv/mckidlet))

Tabs
-----

You can add Tabs to your documentation. This is very usefull when showing how to do something in different programming languages.

```markdown
    <!-- tabs:start -->
    #### **Swift**

    ```swift
    struct Person {
        let firstName: String
        let lastName: String
    }
    ``` 

    #### **Objective C**

    ```objc
    @interface Person : NSObject
    @property (readonly) NSString *firstName;
    @property (readonly) NSString *lastName;
    @end
    ```

    #### **Kotlin**

    ```kotlin
    data class Person(val firstName: String, val lastName: String)
    ```

    <!-- tabs:end -->
```

renders as follows:

<!-- tabs:start -->
#### **Swift**

```swift
struct Person {
    let firstName: String
    let lastName: String
}
``` 

#### **Objective C**

```objc
@interface Person : NSObject
@property (readonly) NSString *firstName;
@property (readonly) NSString *lastName;
@end
```

#### **Kotlin**

```kotlin
data class Person(val firstName: String, val lastName: String)
```

<!-- tabs:end -->
