����ʼ����Ͳο�
http://www.cnblogs.com/dongshuangjie/p/5306307.html
http://forum.aspnetboilerplate.com/viewtopic.php?p=927
https://github.com/aspnetboilerplate/aspnetboilerplate/blob/master/src/Abp/Net/Mail/EmailSettingProvider.cs
http://forum.aspnetboilerplate.com/viewtopic.php?t=87&p=153
����������С��:
1.EmailSettingProvider�����������AbpKernelModule��PostInitialize��ͨ��SetttingManager��ȡ����Provider��ֵ������,��������Ѽ���Provider�Ĵ���ŵ�ģ���PostInitialize����޷�����Abp���EmailSettingProvider���ֵ
2.Abp��ͨ�������ȡAbp.Net.Mail.DefaultFromAddress��Abp.Net.Mail.DefaultFromDisplayName,���������û��,��ȥ���ݿ�AbpSettings����ȡ,�����е�������ֵ��Ǩ��ʱд����Seed��,���Խ���취�Ǹı�������ݻ�ֱ��ɾ������������ֵ

=================================================

���Demo�漰���ķ���:
1.�����ʼ�
2.��ȡ��������ɾ���ļ�¼
3.�����¼�(EntityEvent����)
4.hangfire