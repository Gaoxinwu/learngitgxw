Git is a distributed version control system;
Git is free software distributed under the GPL;
Git has a mutable index called stage.
Git tracks changes of files.
�ֲ�ʽ�汾ϵͳ�����ô�֮һ���ڱ��ع�����ȫ����Ҫ����Զ�̿�Ĵ��ڣ�Ҳ������û������������������������SVN��û��������ʱ���Ǿܾ��ɻ�ģ����������ʱ���ٰѱ����ύ����һ�¾������ͬ��������̫�����ˣ�
Creating a new branch is quick.
git add���ļ���ӽ�ȥ��ʵ���Ͼ��ǰ��ļ��޸���ӵ��ݴ�����
git commit�ύ���ģ�ʵ���Ͼ��ǰ��ݴ��������������ύ����ǰ��֧��
���Ǵ���Git�汾��ʱ��Git�Զ�Ϊ���Ǵ�����Ψһһ��master��֧�����ԣ����ڣ�git commit������master��֧���ύ���ġ�
Git���ٲ���������޸ģ������ļ���
Ҫ��¡һ���ֿ⣬���ȱ���֪���ֿ�ĵ�ַ��Ȼ��ʹ��git clone�����¡��

Git֧�ֶ���Э�飬����https����ͨ��ssh֧�ֵ�ԭ��gitЭ���ٶ���졣
Ҫ����һ��Զ�̿⣬ʹ������git remote add origin git@server-name:path/repo-name.git��
������ʹ������git push -u origin master��һ������master��֧���������ݣ�
�˺�ÿ�α����ύ��ֻҪ�б�Ҫ���Ϳ���ʹ������git push origin master���������޸ģ�

���ҩ��
����1����������˹�����ĳ���ļ������ݣ���ֱ�Ӷ������������޸�ʱ��������git checkout -- file��
����2�����㲻�������˹�����ĳ���ļ������ݣ�����ӵ����ݴ���ʱ���붪���޸ģ�����������һ��������git reset HEAD file���ͻص��˳���1���ڶ���������1������
����3���Ѿ��ύ�˲����ʵ��޸ĵ��汾��ʱ����Ҫ���������ύ���ο��汾����һ�ڣ�����ǰ����û�����͵�Զ�̿⡣
