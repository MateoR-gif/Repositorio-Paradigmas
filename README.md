
--TERCER PUNTO--

object MyClass {

    def main(args: Array[String]) {
        var n = 4
        var result = 1
        while(n > 0){
             result = result * n
            n = n - 1
        }
        print(s"La permutacion circular es: $result ")
    }
}
