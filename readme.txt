<This is a test text>
Git is a version control system.
Git is free software.

�����ĵ���
<�Ա�����>
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

<�����汾�� repository>
$ mkdir ��Ŀ¼���ƣ�
$ cd��Ŀ¼���ƣ�	//��Ŀ¼
$ pwd	//��ʾ��ǰĿ¼

$ git init	//Ŀ¼��ΪGit����ֿ�

<����ļ�>
�����ļ����ڲֿ�Ŀ¼�£���
$ git add ���ļ����ƣ�	//����ļ����ɷ������ʹ�ã���Ӷ���ļ�
$ git commit -m "�����˵����"	//��ӱ����ύ˵��

<�ļ��鿴>
$ git status	//�鿴�ֿ⵱ǰ״̬
$ git diff	//�鿴�޸�����

<�汾����>
$ git log	//�鿴�޸���ʷ
$ git log --pretty=oneline	//����ͬ�ϣ�����ʾ
$ git reset --hard HEAD^	//�ص���һ���汾 ����HEAD^�ϸ��汾 HEAD^^���ϸ��汾 HEAD~n ��n���汾
$ git reset --hard ��commit id�汾�ţ�	//���ݵ�commit id����Ӧ�汾
$ git reflog	//�鿴������ʷ��Ҳ���ҵ�commit id
