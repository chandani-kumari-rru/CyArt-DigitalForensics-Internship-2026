# Security-Awareness-Quiz-Platform
Refer Video: [Supabase v/s Firebase](https://youtu.be/ML3t9t7l0xI?si=G4ilpHAoOKSvugGj)

## Procedure for setup in Windows
- STEP 1: Download WSL & Ubuntu in windows
```
wsl --install
wsl --version
```
- STEP 2: open Ubuntu & run these command one by one
```
sudo apt update
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo bash -
sudo apt install -y nodejs
node --version
npm --version
```
> Supabase SDK requires Node 22+. The default apt node package is often older. Use the NodeSource step above don't skip it.
- copy repo to ur local repo
- STEP 3: Generate SSH & then after copy & paste on [GitHub](https://github.com/settings/keys)
> Since our repo is private so first authenticate through SSH then move forward
```
ssh-keygen -t ed25519
cat ~/.ssh/id_ed25519.pub
```
- STEP 4: Clone git repo
```
git clone git@github.com:CyArt-Tech/Security-Awareness-Quiz-Platform.git
```
- STEP 5: Create Supabase Project & then after collect `project url`,`publishable key` & `secret key`.
```
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_PUBLISHABLE_KEY=
SUPABASE_SECRET_KEY=
```
- STEP 6: Configure `URL`,`PUBLISHABLE_KEY` & `SECRET_KEY` in our project (`.env.local`)
```
cp .env.example .env.local
vi .env.local
:wq
```
- STEP 7: Start the dev server
```
npm run dev
```





























<img width="1917" height="1073" alt="image" src="https://github.com/user-attachments/assets/ae23d12b-61b8-436f-b1c2-61316d697dea" />
