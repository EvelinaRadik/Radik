fun main() {
    print("Enter 6 digits: ")
    val input = readLine()
    
    if (input != null && input.length == 6) {
        val firstHalf = input.substring(0, 3)
        val secondHalf = input.substring(3, 6)
        
        if (firstHalf == secondHalf) {
            println("Lucky ticket!")
        } else {
            println("Unlucky ticket :(")
        }
    } else {
        println("Invalid input. Please enter 6 digits.")
    }
}
