# 4-assignment
rectangle
struct Rectangle {
        width: u32,
        height: u32,
    }
    
    fn area(rectangle: &Rectangle) -> u32 {
        rectangle.width * rectangle.height
    }
    
    
    fn main() {
        let rect1 = Rectangle {
            width: 100,
            height: 50,
        };
    
        println!(
            "The area of the rectangle is {} square pixels.",
            area(&rect1)
        );
    }
    
    
    triangle
    struct Rectangle {
        width: u32,
        height: u32,
    }
    
    fn area(rectangle: &Rectangle) -> u32 {
        rectangle.width * rectangle.height
    }
    
    
    fn main() {
        let rect1 = Rectangle {
            width: 100,
            height: 50,
        };
    
        println!(
            "The area of the rectangle is {} square pixels.",
            area(&rect1)
        );
    }
