<This is a test message>

�����ĵ���
<�Ա�����>
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

<�����汾�� repository>
$ mkdir ��Ŀ¼���ƣ�	//����Ŀ¼
$ cd��Ŀ¼���ƣ�	//��Ŀ¼
$ cat ���ļ����ƣ�	//���ļ�
$ pwd	//��ʾ��ǰĿ¼
$ git init	//Ŀ¼��ΪGit����ֿ�

<����ļ�>
�����ļ����ڲֿ�Ŀ¼�£���
$ git add ���ļ����ƣ�	//����ļ����ݴ�����stage�����ɷ������ʹ�ã���Ӷ���ļ�
$ git commit -m "�����˵����"	//���ݴ��������޸��ύ����֧��ͬʱ������ӱ����ύ˵��

<�ļ��鿴>
$ git status	//�鿴�ݴ�����ǰ״̬
$ git diff	���ļ����ƣ�//�鿴�޸�����

<�汾�����>
$ git log	//�鿴�޸���ʷ
$ git log --pretty=oneline	//����ͬ�ϣ�����ʾ
$ git reset --hard HEAD^	//�ص���һ���汾 ����HEAD^�ϸ��汾 HEAD^^���ϸ��汾 HEAD~n ��n���汾
$ git reset --hard ��commit id�汾�ţ�	//���˵�commit id����Ӧ�汾
$ git reflog	//�鿴������ʷ��Ҳ���ҵ�commit id

<�����޸�>
$ git checkout -- ���ļ����ƣ�	//�ð汾��汾�滻�������汾
$ git reset HEAD ���ļ����ƣ�	//�����ݴ����޸���������

<ɾ���ļ�>
$ git rm ���ļ����ƣ�	//ɾ���ļ�

<���Զ�̿�>
$ git remote add origin ��github��ַ��	//����githubԶ�̿�
$ git push origin master	//master��֧�����޸�����github��$ git push -u origin master ��һ�����ͣ�
