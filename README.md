# Genshin Impact FPS Unlocker
 - This tool helps you to unlock the 60 fps limit in the game
 - This is an external program uses **WriteProcessMemory** to write the desired fps to  the game
 - Handle protection bypass is already included
 - Does not require a driver for R/W access
 - Supports OS and CN version
 - Should works for future updates
 - If the source needs to be updated, I'll try to do it as soon as possible
 - You can download the compiled binary over at 'Release' if you don't want to compile it yourself
 ## Compiling
 - Use  Visual Studio 2019 Community Edition to compile
 - Not required but I know it works on this version
 ## Usage
 - Place the compiled exe into one directory above the game (same folder as launcher.exe)
 - Make sure your game is closed, the unlocker will automatically start the game for you
 - Run the exe as administrator, and leave the exe running
 >It requires adminstrator because the game needs to be started by the unlocker and the game requires such permission
 ### Default Keybinds
 - **END** to toggle on/off
 - **UP ARROW** to increase limit (+20)
 - **DOWN ARROW** to decrease limit (-20)
 - The default fps limit is set to 120
 ## Notes
 - Tested on a new account for two weeks and no bans so far (AR30), can't guaranteed it will be safe forever, But honestly though, I doubt they would ban you for this.
 - Modifying game memory with an unauthorized third party application is a violation of the ToS, so use it at your own risk
 - If you want to change keybinds or the default fps then you can edit the defines at the top of the source
 - [Here](http://cherrytree.at/misc/vk.htm) is a list of keycodes


# ԭ�����FPS����

 - ����ԭ���������ⲿ������ͨ��**WriteProcessMemory**��FPS��ֵд����Ϸ
 - ����Ҫͨ���������ж�д����
 - ֧�ֹ��������
 - ������֧�ֺ����汾������Ҫ����Դ��
 - �����Ҫ�����һᾡ�����

## ����

 - ��VS2019���룬�����汾��ҲӦ�ÿ��ԣ�û���Թ�
## ʳ��ָ��
 - �ѽ������ŵ���Ϸִ���ļ�����һ��Ŀ¼ ����������launcher.exeͬһ��Ŀ¼��
 - ����֮ǰȷ����Ϸ�ǹرյ�
 - �ù���Ա���н�����
 - ���������ܹص�
>ʹ�ù���Ա��������Ϊ��Ϸ�����ɽ�������������Ϸ�������Ҫ����ԱȨ���ˣ����Ը���������Ҳ����Ҫ��
### Ĭ���ȼ�
- **END** ��/��
- **�Ϸ����** ����FPS���� ��+20��
- **�·����** ����FPS���� ��-20��
- Դ��Ĭ�ϵ�FPS��ֵ��120

## ע��
- �Ѿ����º��ϲ����������ڣ�Ŀǰ��û���κ��쳣��ð�յȼ�30
- ʹ��δ��֤�ĵ���������޸���Ϸ������Υ����Э������ģ�����Ը�
- ��Ҫ�����ȼ��Ļ����޸���Դ�￪ͷ�Ķ��� ��[�ȼ���](http://cherrytree.at/misc/vk.htm)��
- Ҫת�صĻ���㣬�Ͼ���Դ�����ԵĻ���ע���³���
- ��ô���ƹ����벻Ҫ��ȥ����