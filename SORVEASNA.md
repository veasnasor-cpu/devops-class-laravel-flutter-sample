# DevOps Conception Class

- Student: [SOR VEASNA]

## Lesson 2: My CI/CD pipeline

- Project: [Personal Financial Mobile App with Laravel API]
- Trigger: [Push to register branch]
- Target: [Staging + test device]

### Pipeline design

Code -> Test -> Build -> Release -> Deploy

1. Code: [action] | [PEN SREYNEAT] | [output] | [auto/manual]
2. Test: [action] | [KHUN TOUCH] | [output] | [auto/manual]
3. Build: [action] | [MOT PHUM] | [output] | [auto/manual]
4. Release: [action] | [SOR VEASNA] | [output] | [auto/manual]
5. Deploy: [action] | [PEN SREYNEAT] | [output] | [auto/manual]

### Controls

On test/build failure: ... | Release approval by: ...
After deployment, check: ... | If it fails: ...
Feedback for the next change: ...
Optional drawing: ![My pipeline](pipeline.png)
