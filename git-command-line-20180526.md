1��git config --list //�鿴������Ϣ
2��git config --global user.name "your name" //--global ���е�Git�ֿⶼ��ʹ���������
3��git config --global user.email "your@email"//--global ���е�Git�ֿⶼ��ʹ���������

4��git init //����ǰĿ¼��ʼ��Ϊgit repository
5��ls -ah�鿴.directory ����Ŀ¼

git add file.txt file2.txt 
git add file3.txt	//����add ����ļ�
git commit -m "�ύ�ı�ע��Ϣ" // add�Ķ���ļ�����һ�����ύ

git status //�鿴��ǰrepository ���������ݴ���״̬
git diff //�鿴�޸ĵ����� ����Ŀ¼working directory�� stage�ݴ����ıȽ�

git reset --hard HEAD^ //HEAD ִ�е��ǵ�ǰ�İ汾 HEAD^ �����ϸ��汾 HEAD^^ ���ϸ��汾 HEAD~n ָ��n���汾ǰ
git log //�鿴�ύ��ʷ commit ����
git log --pretty=oneline //��ӡ��ͬһ��

git reflog //�鿴������ʷ ���еİ汾����  ����commit ��reset ����

git checkout -- file.txt //�����������ļ��ָ��� stage�ݴ����еİ汾(�ݴ�����δcommit���ݣ���Ϊ��һ��commit���ݣ�����ǰ��֧�汾����)
git reset HEAD file.txt //�����ݴ������޸ģ��ָ�δadd֮ǰ���������ı�������ٴ�add

ssh-keygen -t rsa -C "your@email" //������Կ�� ssh-keygen�м�û�пո�
