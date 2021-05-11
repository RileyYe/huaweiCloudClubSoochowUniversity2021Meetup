# 苏州大学华为云俱乐部科研部见面会

+ 题目A ：实现一个vector\<T>

  - vector\<T>的身份证: <https://zh.cppreference.com/w/cpp/container/vector>

  - 基础
  
    现在提供如下的 C++ 代码框架，请你在既有的代码基础上完成功能，使之成为一个 vector\<T>.  注意，在vector\<T>中，所有的元素都是**顺序存储**的，且vector\<T> 可以实现自动扩容(类似于Python的list)。
    
    你应当完成的基本功能在如下代码中，在动手之前，你应当先确保自己熟悉**指针**(如下面的T*)与**模板**(如下面的template关键字)。
    ``` C++
        template <typename T>
        struct vector {
            T*      begin();
            T*      end();
            size_t  size();
            bool    empty();
            void    push_back(const T& value);
            void    push_front(const T& value);
            T&      operator[](size_t index);
        };
    ```
  - 进阶
    
    你已经完成上述需求，但仍觉得意犹未尽？现在可以放飞自我，自由地为vector\<T> 添加功能！只要你觉得是一个`列表`应该提供的功能，现在都可以加到你的vector\<T>中去。还没有好的想法？去最上面看看vector\<T>的身份证吧，看看它在标准库里长啥样。


