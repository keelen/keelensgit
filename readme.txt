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
$ git diff ���ļ����ƣ�	//�鿴�޸�����

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

<Զ�̿����>
$ git remote add origin ��github��ַ��	//����githubԶ�̿�
$ git push origin master	//master��֧�����޸�����github origin��$ git push -u origin master ��һ�����ͣ�
$ git clone ��github��ַ��	//��¡Զ�̿�������
$ git remote ��Զ�ֿ̲⣬Ĭ����origin��	//�鿴Զ�̿���Ϣ
$ git remote -v	//�鿴ץȡ�����͵�ַ
$ git pull	//ץȡԶ���ļ�
$ git checkout -b �����ط�֧���ƣ� origin/��Զ�̿��֧���ƣ�	//�ڱ��ش�����Զ�̷�֧��Ӧ�ķ�֧
$ git branch --set-upstream �����ط�֧���ƣ� origin/��Զ�̿��֧���ƣ�	//�������ط�֧��Զ�̷�֧�Ĺ���

<��֧������鿴>
$ git branch ����֧���ƣ�	//������֧
$ git checkout ����֧���ƣ�	//�л���֧
$ git checkout -b ����֧���ƣ�	//����+�л���֧
$ git branch	//�鿴��֧

<��֧�ϲ�>
$ git merge ��--no-ff�� ����֧���ƣ�	//�ϲ�ָ����֧����ǰ��֧����ͻʱ�޷��ϲ�������--no-ff�����Ϳ�������ͨģʽ�ϲ����ϲ������ʷ�з�֧���ܿ��������������ϲ�
$ git log --graph	//�鿴��֧�ϲ�ͼ

<ɾ����֧>
$ git branch -d ����֧���ƣ�	//ɾ����֧
$ git branch -D feature-vulcan	//ǿ��ɾ��δ���ϲ����ķ�֧

<�ݴ浱ǰ����>
$ git stash	//�ݴ浱ǰ����
$ git stash list	//�鿴�ݴ�������
$ git stash apply	//�ָ�����
$ git stash drop	//ɾ���ݴ�������
$ git stash pop	//�ָ�+ɾ��
$ git stash apply ��stash���ƣ�	//�ָ�ָ��stash


