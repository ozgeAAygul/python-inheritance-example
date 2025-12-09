# python-inheritance-example
A simple Python project demonstrating inheritance and method overriding.
# 🐾 Python OOP — Inheritance Example

Bu proje, Python’da **kalıtım (inheritance)** kavramını öğrenmek ve uygulamak için hazırlanmış basit bir örnektir.  
`Animal` sınıfı temel sınıftır ve `Dog` ile `Cat` sınıfları bu sınıftan miras alır.

---

## 🧱 Kullanılan Kavramlar
- Class (Sınıf)
- Object (Nesne)
- Inheritance (Kalıtım)
- Method Overriding (Metot Ezme)
- `super()` kullanımı

---

## 🐶 Sınıfların Yapısı

### ### `Animal` (Base Class)
- `name`
- `age`
- `speak()` → Genel bir ses döner.

### `Dog` (Child Class)
- `Animal` sınıfından miras alır
- `speak()` → "Woof woof!"
- `fetch()` → Köpeğe özel davranış

### `Cat` (Child Class)
- `Animal` sınıfından miras alır
- `speak()` → "Meow!"
- `sleep()` → Kediye özel davranış

---

## 🧪 Kullanım Örneği

```python
dog = Dog("Loki", 3)
cat = Cat("Mia", 2)

print(dog.speak())   # Woof woof!
print(cat.speak())   # Meow!

print(dog.fetch())   # Dog is fetching the ball!
print(cat.sleep())   # Cat is sleeping...

