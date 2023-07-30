get-childitem *.extension | ForEach { Move-Item -LiteralPath $_.name $_.name.Replace("character you want to rename or remove","new character or set it blank to remove the character")}
