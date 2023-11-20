# fluffy-waffle


main.go

    package main

    import (
        "encoding/json"
        "fmt"

        "github.com/ilmsg/fluffy-waffle/domain"
    )

    func main() {
        user := domain.User{ID: "1", FirstName: "scott"}
        userJSON, _ := json.Marshal(user)
        fmt.Println(string(userJSON))
    }
