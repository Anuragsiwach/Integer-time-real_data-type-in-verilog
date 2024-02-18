# Integer-time-real_data-type-in-verilog
module DataTypesExample;
  // Declare integer variable
  reg [7:0] integer_var;

  // Declare time variable
  time time_var;

  // Declare real variable
  real real_var;

  initial begin
    // Assign integer value
    integer_var = 8;

   // Display integer value
    $display("Integer variable: %d", integer_var);

   // Assign time value
    time_var = 10;

   // Display time value
    $display("Time variable: %t", time_var);

   // Assign real value
    real_var = 3.14;

   // Display real value
    $display("Real variable: %f", real_var);
  end

endmodule
