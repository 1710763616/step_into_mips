��Ŀ¼�ṩ�������ܲ��԰���


������־
--v0.01��20180710
         1.��һ�η�����
--v0.02��20180718
         1.�����ĵ������ܲ���˵��.pdf��Ϊv0.02���޸Ĺ��ּܷ��������ύ˵����
         2.�����ļ�δ�޸ġ�
--v0.03��20180811
         1.�����ĵ������ܲ���˵��.pdf��Ϊv0.03���������ֵĴ���֡������š�
         2.����SoC���Confreg�����ַ����0x0xffff_0000~0xffff_ffff������0xbfaf_0000~0xbfaf_ffff��
         3.����SoC���Testbench������ʹ��negedge clk���ȶ�Trace�����¼��finish�������
         4.����Soft������n75ȡָ��ַ��������ԣ�ʹ����Ը�ȫ�棻
                     ����disable trace���ƣ�ʹ����׳��
                     ����start.S��0xbfc00100��������ģ�⴮��д��0xff��ʾ�������С�
         5.���ϸ��£�����myCPU��ʹ��Trace�ԱȻ��ƣ���myCPU�����debug_wb_rf_wen����㼴�ɹر�testbecnh���Trace�ȶԣ�
                     ����myCPU�����debug_wb_pc����㣬����ʱ��Ȼ������ȷfinish��
         
Ŀ¼�ṹ��
   +--cpu132_gettrace/   : gs132����golden_trace�Ļ������ܹ�ΪSoC_SRAM_Lite��Ĭ��������golden_trace.txt
   |        
   |--soc_axi_func/      : AXI�ӿڵ�CPU���л������ܹ�ΪSoC_AXI_Lite
   |        
   |--soc_sram_func/     : SRAM�ӿڵ�CPU���л������ܹ�ΪSoC_SRAM_Lite
   |        
   |--soft/              : 89�����ܵ���Գ���ͼ�����Ϸ���Գ���Ĭ���Ѱ�������õĽ��
   |        
   |--���ܲ���˵��.pdf   : ���ܲ���˵���ĵ�
   |        
   |--Readme_First.txt   : ���ĵ�