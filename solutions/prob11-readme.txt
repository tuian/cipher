An ECB/CBC detection oracle
题目描述：代码要实现，在明文前面和后面分别延长5-10字节（字节数随机产生），然后将扩展后的明文一半使用ECB模式加密，一半使用CBC模式加密，密钥是随机产生，IV随机产生，使用哪种模式加密哪一半明文也是随机的，最后还要能够区分每一个分组是哪一种模式加密而成的。