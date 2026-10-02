```javascript
/**
 * Hi there, this is 蹦蹦小圆帽!
 * 散厨 / 小男孩系
 */

const baseInfo = {
    name: "蹦蹦小圆帽",
    alt:  ["阿帽", "帽帽"],
    role: ["Cyber Security", "Penetration Tester", "Developer", "Student"],
    location: "🌍 Anywhere on the earth but often in Jinan, CN",
    interests: [
        "Pentesting",
        "Coding",
        "校服 😋",
        "涩涩！！！🥵🥵🥵"
    ],
    learningOn: [
        "C/C++", "Golang"
    ],
    languages: [
        "Java", "Node.js", "Python",
        // of course
        "en_US", "zh_CN", "zh_TW"
    ],
    vibe: () => "这个世界灿烂盛大！🎉"
}

const oneMoreThing = {
    tags: ["小男孩系", "散兵大人万岁", "中推第一涩涩校服控"],
    // 有种你打我呀🙄
    motto: () => [
        "saob就是用来被草的 😋",
        "🥺🥺🥺🥺🥺🥺🥺🥺🥺"
    ]
}

const contactInfo = {
    github: "https://github.com/scaraOvO",
    twitter: "https://x.com/wandererfly"
}

const hobby = () => "涩涩".repeat(3) + "!!! 🥵"; 

module.exports = { baseInfo, oneMoreThing, contactInfo, hobby }
```
