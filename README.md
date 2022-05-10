 a fairly abstract level, super() provides the access to those methods of the super-class (parent class) which have been overridden in a sub-class (child class) that inherits from it. Consider the code example given below, here we have a class named Square and an another class named Cube which inherits the class Square.

class Square: 

     def __init__(self, side): 

         self.side = side 

  

     def area(self): 

         return self.side * self.side 

  

class Cube(Square): 

      def area(self): 

         face_area = self.side * self.side 

         return face_area * 6

  

     def volume(self): 

         face_area = self.side * self.side 

         return face_area * selA file management system is used for file maintenance (or management) operations. It is is a type of software that manages data files in a computer system. A file managemen contains heterogeneous data. It provides high performance, availability, scalability. It supports Geospatial efficiently. It is a document oriented database and the data is stored in BSON documents. It also supports multiple document ACID transition(stringt system has limited capabilities and is designed to manage individual or group files, such as special office documents andf
