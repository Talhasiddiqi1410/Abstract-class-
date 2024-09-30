# Abstract-class-
#include <iostream>

class Animal {
public:
    virtual void makeSound() = 0; // Pure virtual function
};
class Dog : public Animal {
public:
    void makeSound() override {
        std::cout << "Woof!" << std::endl;
    }
};

class Cat : public Animal {
public:
    void makeSound() override {
        std::cout << "Meow!" << std::endl;
    }
};
int main() {
    Dog dog;
    Cat cat;

    dog.makeSound();
    cat.makeSound();

    return 0;
}#include <iostream>

class Animal {
public:
    virtual void makeSound() = 0; // Pure virtual function
};
class Dog : public Animal {
public:
    void makeSound() override {
        std::cout << "Woof!" << std::endl;
    }
};

class Cat : public Animal {
public:
    void makeSound() override {
        std::cout << "Meow!" << std::endl;
    }
};
int main() {
    Dog dog;
    Cat cat;

    dog.makeSound();
    cat.makeSound();

    return 0;
}#include <iostream>

class Animal {
public:
    virtual void makeSound() = 0; // Pure virtual function
};
class Dog : public Animal {
public:
    void makeSound() override {
        std::cout << "Woof!" << std::endl;
    }
};

class Cat : public Animal {
public:
    void makeSound() override {
        std::cout << "Meow!" << std::endl;
    }
};
int main() {
    Dog dog;
    Cat cat;

    dog.makeSound();
    cat.makeSound();

    return 0;
}#include <iostream>

class Animal {
public:
    virtual void makeSound() = 0; // Pure virtual function
};
class Dog : public Animal {
public:
    void makeSound() override {
        std::cout << "Woof!" << std::endl;
    }
};

class Cat : public Animal {
public:
    void makeSound() override {
        std::cout << "Meow!" << std::endl;
    }
};
int main() {
    Dog dog;
    Cat cat;

    dog.makeSound();
    cat.makeSound();

    return 0;
}
