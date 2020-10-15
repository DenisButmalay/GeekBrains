import Foundation
protocol Car{
func CarDrive()->Bool
}
class SportCar{
    var wheels=4
    var color:String
    var windows:Bool
    var brand:String
    
    init(color: String, windows: Bool,brand:String ) {
        self.color=color
        self.windows=windows
        self.brand=brand
    }
    func CanDrive()->Bool {
        if wheels != 4 {
            print("Oops,you have some problems with wheels")
            return false
            
        } else {
            print("All wheels are fine")
            return true
  }
 }
}
class TrunkCar:Car{
    var gruzopod:Int
    var zapashoda:Int
    var razia: Bool
    init(gruzopod:Int,zapashoda:Int,razia: Bool) {
        self.gruzopod=gruzopod
        self.zapashoda=zapashoda
        self.razia=razia
    }
    func CarDrive() -> Bool {
        if zapashoda < 1000 {
            print ("Sorry, you need to fill you tank")
            return false
        }else{
            print ("Have a good ride")
            return true
        }
}
}
extension SportCar{
    func checkwindows()-> Bool{
        if windows == true{
            print("You can drive")
            return true
        } else {
            print("Close your windows,please")
            return false
        }
    }
}
extension TrunkCar{
    func checkrazia()->Bool{
        if razia == true{
            print ("Good luck")
            return true
        }else{
            print ("Please take your razia")
            return false
        }
    }
}
extension SportCar: CustomStringConvertible{
    var description: String {
        return String(describing: color)
    }
}
extension TrunkCar: CustomStringConvertible{
    var description: String {
        return String(describing: zapashoda)
    }
}

let M5=SportCar(color: "Blue", windows: false, brand: "BMW")
let Eclass=SportCar(color: "Black", windows: true, brand: "Mersedes")
let MAG=TrunkCar(gruzopod: 1200, zapashoda: 1500, razia: false)
let UAZ=TrunkCar(gruzopod: 1000, zapashoda: 800, razia: true)

M5.color
M5.windows
M5.brand
Eclass.color
Eclass.windows
Eclass.brand
UAZ.gruzopod
UAZ.zapashoda
UAZ.razia
MAG.gruzopod
MAG.zapashoda
MAG.razia
//Это чтобы показать работу имплементирующего протокола CustomStringConvertible
M5
Eclass
UAZ
MAG
