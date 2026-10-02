# DevOps Conception Class

- Student: SOR VEASNA

## Lesson 2: My CI/CD pipeline

- Project: Personal Financial Mobile App with Laravel API
- Trigger: Push to `feature/register` branch
- Target: Staging + test device

### Pipeline design

Code -> Test -> Build -> Release -> Deploy

1. Code: [action] | [PEN SREYNEAT] | [Register Screen] | [manual]
2. Test: [action] | [KHUN TOUCH] | [check register Screen] | [auto/manual]
3. Build: [action] | [MOT PHUM] | [apk file] | [auto]
4. Release: [action] | [SOR VEASNA] | [apk file v.0.0.1] | [auto]
5. Deploy: [action] | [PEN SREYNEAT] | [apk file v.0.0.1] | [auto]

### Controls

On test/build failure: notify to group chat | Release approval by: MOT PHUM
After deployment, check: login, register, and other features | If it fails: Contact to PEN SREYNEAT
Feedback for the next change: require to update the code or change the logic
Optional drawing: ![My pipeline](image.png)
