```swift
import Foundation

struct Profile {
    let name: String
    var age: Int
    let job: String
    let github: URL?
    let blog: URL?
}

let jihoonAHN = Profile(name: "JiHoonAHN",
                        age: 20,
                        job: "iOS Developer",
                        github: URL(string: "https://github.com/JiHoonAHN"),
                        blog: URL(string: "https://blog.jihoon.me"))
print(jihoonAHN)
```

