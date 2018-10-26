# Data-Construction
package one;

public interface LList<T>
{	               
    //线性表接口，泛型参数T表示数据元素的数据类型
    
    boolean isEmpty();            //判断线性表是否空
    
    int size();                        //返回线性表长度
    
    T get(int i);                         //返回第i（i≥0）个元素
    
    void set(int i, T x);             //设置第i个元素值为x
    
    void insert(int i, T x);        //插入x作为第i个元素
    
    void insert(T x);             //在线性表最后插入x元素
    
    T remove(int i);                //删除第i个元素并返回被删除对象
    
    int search(T key);          //查找，返回首次出现的关键字为key的元素的位序
    
    void removeAll();             //删除线性表所有元素
    
    public String toString();     //返回顺序表所有元素的描述字符串，形式为“（，）”
}
