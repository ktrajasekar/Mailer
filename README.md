		<tr>
			<td style="padding:5px;"><?php echo $order->get_formatted_billing_address(); ?> </td>
			<td style="padding:5px;"><?php echo $order->get_formatted_shipping_address(); ?> </td>
		</tr>
    
    <p>
  Dear <?php printf( __( '%s', 'woocommerce' ), $order->get_formatted_billing_full_name() ); ?>,
</p>
