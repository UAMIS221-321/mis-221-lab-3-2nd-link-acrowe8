//main
GetEnjoymentLevel();
GetStadiumReconommendation(enjoymentLevel);
GetGameReconommendation(stadium);
DisplayStadiumDetails();
//end main

GetEnjoymentLevel(){
    System.Console.Writeline("What enjoyment level are you looking for?");
    String enjoymentLevel = System.Console.Realine();
}

GetStadiumReconommendation(string enjoymentLevel){
    if enjoymentLevel == "boring"
        String boring = "Neyland";
    if else enjoymentLevel == "average"
        String average = "Jordan-Hare";
    if else enjoymentLevel == "fun"
        String fun = "Tiger;
    if else enjoymentLevel == "epic"
        String epic = "Saban Field";
}

GetGameRecommendation(string stadium){
    if stadium == "Neyland"
        string neyland = "Kent state";
    if else stadium = "Jordan-Hare"
        string jordanHare = "Kentucky";
    if else stadium == "Tiger"
        String tiger == "Alabama";
    if else stadium == "Saban"
        String saban = "Auburn";
}

DisplayStadiumDetails(string stadium, string game){
    System.Console.WriteLine("You should go to "+stadium+" and see the "+game);
}