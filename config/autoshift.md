as: auto_shift {
    compatible = "zmk,behavior-hold-tap";
    label = "AUTO_SHIFT";
    #binding-cells = <2>;
    tapping_term_ms = <175>;
    quick_tap_ms = <0>;
    flavor = "tap-preferred";
    bindings = <&kp>, <&kp>;
};