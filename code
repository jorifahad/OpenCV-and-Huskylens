#include "HUSKYLENS.h"
#include "Wire.h"

HUSKYLENS huskylens;

void setup() {
    Serial.begin(115200);
    Wire.begin();
    
    if (!huskylens.begin(Wire)) {
        Serial.println("Huskylens not connected!");
        while (1);
    } else {
        Serial.println("Huskylens connected!");
    }
}

void loop() {
    if (huskylens.request()) {
        if (huskylens.isLearned()) {
            for (int i = 0; i < huskylens.countBlocks(); i++) {
                int faceID = huskylens.blocks[i].ID;
                
                Serial.print("Face Detected! ID: ");
                Serial.println(faceID);
            }
        } else {
            Serial.println("No face detected.");
        }
    }
    delay(500);
}
