var user = prompt("You are walking through a forest. As you pass by the sunlit tree by the waterfall, you see a beautiful young woman, playing a harp. Would you like to CONTINUE WALKING, TALK to her, or ATTACK her?").toUpperCase();

switch(user) {
    
    case "CONTINUE WALKING":
        console.log("You pass her by as you continue walking, but you hear her call out to you. You turn around.");
        var walk = prompt("Do you TALK back to her, or KEEP WALKING?").toUpperCase();
            if (walk === "TALK") {
                console.log("As you TALK to her, she asks you to drink from the waterfall.");
                console.log("You drink it. It turns out the water from the waterfall has a spell on it! You collapse to the ground. You have fallen in to the trap and have been defeated by the White Enchantress!");
        }   else if (walk === "KEEP WALKING") {
                console.log("You have escaped from the trap of the White Enchantress! You have passed the test!");
        }   else {
            console.log("Please enter TALK or KEEP WALKING")
        };
        break;
        
    case "TALK":
        console.log("You approach her to TALK to her. As she continues to play, she smiles and says, 'At long last, you are here, my dear.'");
        var talking = prompt("You are wondering why she is expecting you! Would you like to ASK her who she is, WALK AWAY, or ATTACK her?");
        if (talking === "ASK") {
            console.log("She reveals herself to be the White Enchantress!");
            console.log("Oh no! You realized you have fallen in to her trap! There is no way to defeat her. You lose!");
        }   else if (talking === "ATTACK") {
            console.log("You ATTACK the young lady. There is a blinding white light, and she reveals herself to be the White Enchantress! There is no way to defeat her, you lose!")    
        }   else if (talking === "WALK AWAY") {
            console.log("You have escaped from the trap of the White Enchantress! Congratulations! You have passed the test!");
        }   else {
            console.log("Please enter ASK, WALK AWAY, or ATTACK")
        }
        break;

    case "ATTACK":
        console.log("You move to ATTACK her with your sword! All of a sudden, a piercing white light shines and consumes everything around you. You cannot see. You realize that you have stumbled in to the trap of the White Enchantress! There is no way to defeat her. You lose!");
        break;

    default:
        console.log("Please select CONTINUE WALKING, TALK, or ATTACK!");
};
