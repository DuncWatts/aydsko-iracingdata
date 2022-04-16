## Aydsko.iRacingData.Common Namespace
- **[CarClass](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass 'Aydsko.iRacingData.Common.CarClass')** `Class` Information on a group of cars considered in the same class.
  - **[CarClassId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.CarClassId 'Aydsko.iRacingData.Common.CarClass.CarClassId')** `Property` Unique identifier for the car class.
  - **[CarsInClass](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.CarsInClass 'Aydsko.iRacingData.Common.CarClass.CarsInClass')** `Property` Individual cars which make up this class.
  - **[CustomerId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.CustomerId 'Aydsko.iRacingData.Common.CarClass.CustomerId')** `Property` Unique identifier of the iRacing Member.
  - **[Name](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.Name 'Aydsko.iRacingData.Common.CarClass.Name')** `Property` Name of the car class.
  - **[RelativeSpeed](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.RelativeSpeed 'Aydsko.iRacingData.Common.CarClass.RelativeSpeed')** `Property` Value indicating the relative speed of this car class.
  - **[ShortName](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.CarClass.ShortName 'Aydsko.iRacingData.Common.CarClass.ShortName')** `Property` A shortened version of the car class' name.
- **[ChunkInfo](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo 'Aydsko.iRacingData.Common.ChunkInfo')** `Class` Summary details of a large data set which has been split into "chunks".
  - **[BaseDownloadUrl](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo.BaseDownloadUrl 'Aydsko.iRacingData.Common.ChunkInfo.BaseDownloadUrl')** `Property` Common part of the URL for each chunk.
  - **[ChunkFileNames](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo.ChunkFileNames 'Aydsko.iRacingData.Common.ChunkInfo.ChunkFileNames')** `Property` List of the filename for each chunk.
  - **[ChunkSize](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo.ChunkSize 'Aydsko.iRacingData.Common.ChunkInfo.ChunkSize')** `Property` Size of each chunk.
  - **[NumChunks](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo.NumChunks 'Aydsko.iRacingData.Common.ChunkInfo.NumChunks')** `Property` The number of chunks the data was split into.
  - **[Rows](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ChunkInfo.Rows 'Aydsko.iRacingData.Common.ChunkInfo.Rows')** `Property` Total number of rows.
- **[DataResponse&lt;TData&gt;](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.DataResponse_TData_ 'Aydsko.iRacingData.Common.DataResponse<TData>')** `Class` Common elements of an API response.
  - **[Data](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.DataResponse_TData_.Data 'Aydsko.iRacingData.Common.DataResponse<TData>.Data')** `Property` Data returned from the API call.
  - **[RateLimitRemaining](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.DataResponse_TData_.RateLimitRemaining 'Aydsko.iRacingData.Common.DataResponse<TData>.RateLimitRemaining')** `Property` Amount of rate limit remaining.
  - **[RateLimitReset](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.DataResponse_TData_.RateLimitReset 'Aydsko.iRacingData.Common.DataResponse<TData>.RateLimitReset')** `Property` Instant at which the rate limit will be reset.
  - **[TotalRateLimit](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.DataResponse_TData_.TotalRateLimit 'Aydsko.iRacingData.Common.DataResponse<TData>.TotalRateLimit')** `Property` The current total rate limit.
- **[ErrorResponse](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ErrorResponse 'Aydsko.iRacingData.Common.ErrorResponse')** `Class` Error details returned by the API.
  - **[ErrorCode](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ErrorResponse.ErrorCode 'Aydsko.iRacingData.Common.ErrorResponse.ErrorCode')** `Property` Identifying code of the error.
  - **[ErrorDescription](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.ErrorResponse.ErrorDescription 'Aydsko.iRacingData.Common.ErrorResponse.ErrorDescription')** `Property` Descriptive text of the error.
- **[Helmet](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet 'Aydsko.iRacingData.Common.Helmet')** `Class` Details about the driver's helmet.
  - **[Color1](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.Color1 'Aydsko.iRacingData.Common.Helmet.Color1')** `Property` First pattern color.
  - **[Color2](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.Color2 'Aydsko.iRacingData.Common.Helmet.Color2')** `Property` Second pattern color.
  - **[Color3](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.Color3 'Aydsko.iRacingData.Common.Helmet.Color3')** `Property` Third pattern color.
  - **[FaceType](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.FaceType 'Aydsko.iRacingData.Common.Helmet.FaceType')** `Property` Identifier for the face type of the driver.
  - **[HelmetType](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.HelmetType 'Aydsko.iRacingData.Common.Helmet.HelmetType')** `Property` Identifier for the type of helmet of the driver.
  - **[Pattern](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Helmet.Pattern 'Aydsko.iRacingData.Common.Helmet.Pattern')** `Property` Identifier of the helmet pattern.
- **[License](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License 'Aydsko.iRacingData.Common.License')** `Class` License information.
  - **[Category](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.Category 'Aydsko.iRacingData.Common.License.Category')** `Property` Name of the license category.
  - **[CategoryId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.CategoryId 'Aydsko.iRacingData.Common.License.CategoryId')** `Property` Identfier for the license category.
  - **[Color](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.Color 'Aydsko.iRacingData.Common.License.Color')** `Property` Color associated with the license.
  - **[GroupId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.GroupId 'Aydsko.iRacingData.Common.License.GroupId')** `Property` Identifier of the license group.
  - **[GroupName](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.GroupName 'Aydsko.iRacingData.Common.License.GroupName')** `Property` Name of the license group.
  - **[LicenseLevel](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.LicenseLevel 'Aydsko.iRacingData.Common.License.LicenseLevel')** `Property` An indicator of the level of the license.
  - **[SafetyRating](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.License.SafetyRating 'Aydsko.iRacingData.Common.License.SafetyRating')** `Property` Value of the safety rating attached to the license.
- **[Suit](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit 'Aydsko.iRacingData.Common.Suit')** `Class` Details about the driver's suit.
  - **[BodyType](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit.BodyType 'Aydsko.iRacingData.Common.Suit.BodyType')** `Property` Type of body chosen for the driver.
  - **[Color1](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit.Color1 'Aydsko.iRacingData.Common.Suit.Color1')** `Property` First pattern color.
  - **[Color2](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit.Color2 'Aydsko.iRacingData.Common.Suit.Color2')** `Property` Second pattern color.
  - **[Color3](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit.Color3 'Aydsko.iRacingData.Common.Suit.Color3')** `Property` Third pattern color.
  - **[Pattern](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Suit.Pattern 'Aydsko.iRacingData.Common.Suit.Pattern')** `Property` Pattern identifier chosen for the suit.
- **[Track](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track 'Aydsko.iRacingData.Common.Track')** `Class` Information about a track.
  - **[Category](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track.Category 'Aydsko.iRacingData.Common.Track.Category')** `Property` Track category name.
  - **[CategoryId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track.CategoryId 'Aydsko.iRacingData.Common.Track.CategoryId')** `Property` Track category identifier
  - **[ConfigName](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track.ConfigName 'Aydsko.iRacingData.Common.Track.ConfigName')** `Property` Track configuration name.
  - **[TrackId](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track.TrackId 'Aydsko.iRacingData.Common.Track.TrackId')** `Property` Identifier for the track.
  - **[TrackName](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.Track.TrackName 'Aydsko.iRacingData.Common.Track.TrackName')** `Property` Name of the track.
- **[EventType](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType 'Aydsko.iRacingData.Common.EventType')** `Enum` The type of the event.
  - **[Practice](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType.Practice 'Aydsko.iRacingData.Common.EventType.Practice')** `Field` Event was a practice session.
  - **[Qualify](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType.Qualify 'Aydsko.iRacingData.Common.EventType.Qualify')** `Field` Event was a qualifying session.
  - **[Race](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType.Race 'Aydsko.iRacingData.Common.EventType.Race')** `Field` Event was a race session.
  - **[TimeTrial](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType.TimeTrial 'Aydsko.iRacingData.Common.EventType.TimeTrial')** `Field` Event was a time trial session.
  - **[Unknown](Aydsko.iRacingData.Common#Aydsko.iRacingData.Common.EventType.Unknown 'Aydsko.iRacingData.Common.EventType.Unknown')** `Field` Event type was not known.