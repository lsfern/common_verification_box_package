## flutter验证码组件
#### 使用
```
  dependency_overrides:
    common_verification_box_package:
      git:
        url: https://github.com/lsfern/common_verification_box_package.git
        ref: main
```
- 新增clearInput方法，使用GlobalKey<VerificationBoxState>去调用
