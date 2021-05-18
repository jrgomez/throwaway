# throwaway

## making changes
file changed on the main branch. 

### changes on main before moving to dev branch
```
//
//  Genre.swift
//  MyMovies
//
//  Created by Joseph Gomez on 5/12/21.
//

import Foundation

struct Genre: Decodable, Identifiable {
var id: String { name }
let name: String
let color: String

static let all = Dictionary( uniqueKeysWithValues: Bundle.main.decode([String: Genre].self, from: "genres.json").map { (Int($0) ?? 0, $1) })
}
```
just a simple code sample from Paul@hackingwithswift.com during iOS accelerator. 
Great class/session. 
