# coolkids-hacktx
Bands/Artists:
    bandName
    bandGenre
    bandShows
    bandLocation
    bandPhoto
    bandLinks

    //bandRating

User:
    username
    password

Fan: Inherit from User
    fanGenres
    fanLocation


Poster: Inherits from User
    posterVerification
    posterType:
        artist/venue
    
Venue:
    venueActs
    venueLocation
    venueName
    venuePicture
    //venueRating

Acts:
    actDate
    actTime
    actVenue
    actArtist
    actPrice 

Search
    location
    range

