import UIKit
enum CarEngine{
    case on, off
}

enum CarDoor{
    case open, close
}
class car {
    let color: String
    let transmition: String
    let horsepower: Double
    let probeg: Int
    var engineState: CarEngine
    var doorState: CarDoor
    init(color:String,transmition: String, horsepower: Double, probeg:Int,engineState:CarEngine,doorState:CarDoor) {
        self.color=color
        self.transmition=transmition
        self.horsepower=horsepower
        self.probeg=probeg
        self.doorState=doorState
        self.engineState=engineState
    }
}
let auditt=car(color: "white", transmition: "robot", horsepower: 249.00, probeg: 12000, engineState: .on, doorState: .open)
let bmwx5=car(color: "red", transmition: "automatic", horsepower: 349.00, probeg: 35000, engineState: .off, doorState: .close)
class sportCar: car{
    let look:Bool
    let autopilot:Bool
    let podsvetka:String
    let fuel:String
    init(color:String,transmition: String, horsepower: Double, probeg:Int,look:Bool,autopilot:Bool,podsvetka:String,fuel:String) {
        self.look=look
        self.autopilot=autopilot
        self.podsvetka=podsvetka
        self.fuel=fuel
        super.init(color: color, transmition: transmition, horsepower: horsepower, probeg: probeg, engineState: .on, doorState: .open)
}
    func openeddoors(){
        doorState = .open
        print("Ваши двери открыты,закройте их пожалуйста")
    }
    func closeddoors(){
        doorState = .close
        print("Ваши двери закрыты,все отлично")
    }
}
let ferrari=sportCar(color: "red", transmition: "variator", horsepower: 440.00, probeg: 1000, look: true, autopilot: false, podsvetka: "purple", fuel: "dizel")
class trunkCar:car{
    var gruzopod:Int
    var zapashoda:Int
    var razia: Bool
    init(color: String, transmition: String, horsepower: Double, probeg: Int,gruzopod:Int,zapashoda:Int,razia:Bool) {
        self.gruzopod=gruzopod
        self.zapashoda=zapashoda
        self.razia=razia
        super.init(color: color, transmition: transmition, horsepower: horsepower, probeg: probeg, engineState: .off, doorState: .close)
    }
}
let MAG=trunkCar(color: "black", transmition: "mechanic", horsepower: 350.00, probeg: 500, gruzopod: 5000, zapashoda: 1000, razia: true)
print(ferrari .horsepower)
print(ferrari.engineState)
print(ferrari.doorState)

